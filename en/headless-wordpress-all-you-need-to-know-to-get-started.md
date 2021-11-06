# Headless WordPress - All you need to know to get started

For some years now, we have been hearing terms like **JAMStack** or **Headless** sites, and these are terms that have become popular in this time that refer to `what` we use and `how` we make websites.

The first thing to understand is that when referring to **JAMStack** or **Headless** sites, we are talking about a development architecture, in this case, web development, this architecture suggests a set of best practices focused on obtaining better performance, better security, lower costs and scalability.

## What is JAMstack?

The term JAMStack was conceived in 2015 by Mathias Biilmann, CEO of [Netlify](https://www.netlify.com/), to describe what has already been said, a web development architecture based on Javascript for the client-side, reusable APIs, and Markup.

As you can see, there are two constants, Javascript and Markup (HTML), but he never tells anything about frameworks, server-side languages, types of APIs. The combinations are immense, and we can use Angular, a REST API created in .NET, VueJS consuming Markdown, ReactJS consuming a GraphQL API on top of Laravel (PHP), ReactJS consuming the WordPress REST API, or just Javascript consuming JSON files.

## What is a Headless CMS?

A Headless CMS uses the JAMStack architecture but with the big difference that the front-end, back-end, and database(s) are independent entities and work without knowledge of each other.

Some developers describe this as `decoupling` the presentation layer (front-end) from the logic and information layer (back-end and databases).

Your front-end and your CMS are no longer permanently tied, but they can still communicate with each other and do so via an API.

What does this mean for developers?

**Freedom**

The front-end developer no longer has to develop the site using a language he doesn't know well, use template engines like blade, or mix PHP into the HTML.

If we are talking about WordPress, the back-end developer won't have to worry about adding X or Y. As long as the information is still delivered through an API, the front-end developer doesn't care about anything.

Now that we are clear on the two concepts, it is time to answer what I believe are the most frequently asked questions on this topic, strictly referring to a headless WordPress.

### What is headless WordPress?

A Headless WordPress is a site that uses the old reliable WordPress admin to handle all the site's content and, on the other hand, a custom front-end to display that content to the site visitor.

### Is headless WordPress better than regular WordPress?

Neither is better or worse than the other, as everything in the developing world depends on the project's characteristics.

### Is Headless WordPress more secure?

Yes, one advantage of having the front-end decoupled is that the visitor/attacker does not know the domain or subdomain where WordPress is hosted. And therefore, they will not be able to, for example, try to use brute force to attack the WordPress login neither have access to the admin.

### Should I use headless WordPress?

A headless WordPress is certainly not for everyone. You should keep in mind that you need to be a developer or hire a developer to take care of the front-end as it is a custom development and external to WordPress.

If you go for a headless WordPress, forget about plugins, page builders, theme options, etc.

On the other hand, if you have the knowledge or budget to migrate your current WordPress to a headless WordPress, the answer is YES. Without a doubt, you add many improvements and benefits to your architecture by using headless WordPress.

### Is WordPress a decoupled CMS?

Not by default, but with custom development, you can use WordPress as a decoupled CMS.

### Pros of using WordPress headless?

- Better Performance. We are serving only HTML, CSS, and Javascript, which are the languages of the web.
- Improves security
- We can have the back-end on one server and the front-end on a different one, even using different platforms.
- Flexibility and control for developers.
- Easier to build Progressive Web Apps (PWA).
- Projects become more scalable at the front-end level.
- Reuse of web components.
- We can develop native mobile applications fetching the data from the same source.
- Savings in hosting costs.
- Modern tooling.

### Cons of using WordPress headless?

- You need the knowledge to develop front-end
- You need a budget to hire a front-end developer
- You need to maintain two projects, the back-end, and the front-end
- You need to pay for two hostings, one for the back-end and one for the front-end (the front-end cost should be cheaper).
- You can't use page builders, plugins, theme options.

### Who should use headless WordPress?

- You are part of a company looking for a robust CMS that supports multi-channel publishing.
- You're a developer who wants to experiment with WordPress and other languages or frameworks.
- You want to create an application and connect it to a CMS to fill it with content.
- You are interested in speeding up your website and improving security along with these other benefits.
- You're familiar with WordPress and want to continue using it, but you're ready to branch out to other technologies.

### Who shouldn't use Headless WordPress?

- You have no web development experience.
- You're not familiar with headless CMSes at all.
- You're not prepared to deal with the configuration required to optimize security and performance.
- Want to make use of the wide variety of WordPress plugins and themes.
- You want to have a simple blog or small business website without the need to publish to multiple channels.
- You want to continue using a page builder.

### What APIs can I use to create my headless WordPress?

WordPress by default incorporates a REST API, but there is also a free plugin to expose a GraphQL API.

Now you know what JAMStack and headless WordPress are, plus you know if a headless WordPress is for you or not.

By the way, this site is a headless WordPress using [GatsbyJS](https://www.gatsbyjs.com/), and the front-end is hosted on [Netlify](https://www.netlify.com/).

If something is unclear, you have any questions, or you are ready to make the switch from a traditional WordPress to a headless WordPress, I can help you. Just ping me on [Twitter](https://www.netlify.com/) or drop me an [email](https://enriquechavez.co/contact).
