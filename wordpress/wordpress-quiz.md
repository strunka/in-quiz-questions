#### Q1. In WordPress, what is the Loop used to do?
- [ ] It displays a single page.
- [ ] It displays posts on an archive.
- [ ] It displays a single post.
- [✔] all of these answers

#### Q2.Who owns the trademark for WordPress and WordCamp names and logos?
- [✔] WordPress Foundation (The WordPress Foundation owns and oversees the trademarks for the WordPress and WordCamp names and logos.)
- [ ] WordPress.com
- [ ] Matt Mullenweg
- [ ] Automattic

#### Q3. 
- [ ] HackerOne
- [ ] Redmine
- [ ] Trac
- [ ] GitHub Issues

#### Q4. The REST API is a simple way to get data in and out of WordPress over HTTP. Applications using the REST API should be written in which programming language?
- [ ] PHP
- [✔] any programming language that can make HTTP requests and interpret JSON
- [ ] Java
- [ ] Node.js

#### Q5. How many minutes does it take to install WordPress according to the "Famous X-Minute Installation" instructions on WordPress.org?
- [✔] 5
- [ ] 30
- [ ] 15
- [ ] 10

#### Q6. In WordPress, what is true of plugins?
- [ ] Plugins are available in free or premium (paid) versions.
- [ ] Plugins can extend WordPress core functionality.
- [✔] all of these answers
- [ ] Plugins add site-specific features.

#### Q7. Akismet is a plugin that comes automatically installed with WordPress. What does it do?
- [ ] It connects your site to Google Analytics.
- [ ] It displays a blog feed from websites similar to yours.
- [✔] It protects your site from comment spam.
- [ ] It hardens site security by enforcing strong passwords.

#### Q8. What would you do to improve your site's performance?
- [ ] Only load scripts and styles on pages where they are needed.
- [ ] Minify CSS and JavaScript files.
- [✔] all of these answers
- [ ] Use a CDN.

#### Q9. The REST API utilizes which data format?
- [ ] YAML
- [✔] JSON
- [ ] TXT
- [ ] XML

#### Q10. What color is the paragraph nested within the div? 
```<html>
<head>
        <style>
                body { color: black; }

                p { color: blue; }

                div { color: green; }

                p { color: red; }
        </style>
</head>
<body>
        <div>
                <p>This is a paragraph inside a div.</p>
        </div>
</body>
</html>
```
- [ ] blue
- [ ] black
- [✔] red
- [ ] green

#### Q11. Theme developers can take advantage of the Customizer API to give users a way to manipulate basic theme settings. The Customizer API is object-oriented and provides four main objects. What are they?
- [ ] widgets, containers, sections, settings
- [ ] containers, hooks, settings, styles
- [ ] panels, blocks, controls, settings
- [ ] panels, sections, controls, settings

#### Q12. Which WordPress setting would you use to make page URLs look like `http://example.com/my-page/` instead of the default `http://example.com/?p=21/?`
- [ ] Writing
- [✔] Permalinks
- [ ] Pretty URLs
- [ ] Reading

#### Q13. In WordPress, what is the block editor used for?
- [ ] cropping images in the media library
- [ ] injecting specialized scripts into the content area
- [✔] creating a site layout
- [ ] creating and laying out content

#### Q14. Which of the following file types is NOT involved in translating WordPress?
- [ ] .po
- [✔] .pot
- [ ] .mot
- [ ] .mo

#### Q15. What is the default priority for an action hook or filter?
- [✔] 10
- [ ] 15
- [ ] 0
- [ ] 5

#### Q16. What user role would you assign to someone so they can write and publish only their posts and no one else´s?
- [ ] Subscriber
- [ ] Editor
- [ ] Contributor
- [ ] Author

#### Q17. You have a webpage that is loading slowly. How can you analyze the page to determine the culprit(s)?
- [ ] Use a plugin like Query Monitor or Debug Bar.
- [ ] Use an online tool like GTmetrix, Pingdom, Lighthouse, or WebPageTest
- [ ] Use your web browser´s developer tools.
- [ ] all of these answers

#### Q18. The Block API enables developers to register custom blocks in themes or plugins. How would you register a custom block?
- [ ] Use the registerBlockType() function.
- [ ] Use the createGutenBlock() function.
- [ ] Use the registerBlockName() function.
- [ ] Use a block template.

#### Q19. WP_Query is the WordPress query class that is used to fetch posts from database. How would you create a new instance of this class?
- [ ] $query = new query_posts();
- [ ] $query = new WP_Query();
- [ ] $query = get_posts();
- [ ] $query = query_posts();

#### Q20. What is a user role that is unique to WordPress Multisite?
- [ ] Owner
- [ ] Multisite Master
- [ ] MU admin
- [ ] Super Admin

#### Q21. You might see this code in a WordPress plugin. What does it do?

if ( ! defined( 'ABSPATH' ) ){
   die;
}

- [ ] This is a compatibility checker. ABSPATH is defined in WordPress core. The plugin checks that the minimum version of WordPress needed to support the plugin is installed. If it is not, the plugins should not run.
- [ ] This is security measure. ABSPATH is the absolute path to the WordPress directory. If the file is called directly, ABSPATH will not be defined and therefore the plugin should not run.
- [ ] This is how WordPress detects a plugin's presence. This ensures that the plugin is running from the /wp-content-plugins/ directory. If it is not, the plugin should not run.
- [ ] This is a way to prevent naming collisions. ABSPATH is the absolute path to the plugin's directory. If ABSPATH is defined by another WordPress plugin with the same directory slug, the plugin should not run.
