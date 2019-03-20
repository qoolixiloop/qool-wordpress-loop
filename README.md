<h1 align="center"> qool-wordpress-loop.wiki </h1>
<h2 align="center"> How to build a website with WordPress</h2>

# My WebSite
You can visit my website:  
https://qoolixiloop.wordpress.com

## Screenshots of my website
I have chosen a free plan at WordPress.com and have built my website with the Lodestar theme from Automattic the company behind WordPress.com. 

The following screenshots of this section show the main parts of my website.

### HOME page
My HOME page contains an overview, in which I explain the main parts of my website. For ech tab of the navigation bar, I wrote a short introduction and added a picture or an embedded video.  

![wp-com-site-home1][2010]  

![wp-com-site-home2][2020]  

![wp-com-site-home3][2030]  

![wp-com-site-home4][2040]  

![wp-com-site-home5][2050]  

![wp-com-site-home6][2060]  

![wp-com-site-home7][2070]  

### POSTS page
The POSTS page displays my blog post summaries ordered by date. In the settings of my website, I have chosen to show 10 blog post summaries per site. The image below shows a blog post summary about WordPress.  

![wp-com-site-posts][2080]  

### A POST page
By clicking the blog title the blog post is loaded into the browser. 

![wp-com-site-posts-post][2090]    

### PROJECTS page
The PROJECTS page shows a picture for each of my projects. By hovering over the picture a link becomes visible. 

![wp-com-site-projects][2110]  

### A PROJECT page
Clicking the link for my Linux project opens my project page about Linux. The two images below show a picture and a short introduction at the beginning and another picture or animation at the end of my project page. In between are sections, which summarize my work and link to either blog posts or GitHub pages, where I host my software as well as tutorials and wiki-pages.  

![wp-com-site-projects-project1][2120] 

![wp-com-site-projects-project2][2130]  

### TESTIMONIALS page
The TESTIMONIALS page, is a summary about what I think, people would say about me. The reason, why I do not use real people, is because I deeply abhor the concept of recommendations. If certifications aren't enough, the companies and universities should do a better job, when writing them. It would be so simple to set up a website with data base, where everyone can check, whether a certificate is authentic.  
  
![wp-com-site-testimonials][2140]  

### ABOUT ME page
The about me page is some kind of CV followed by my certificates, the attended lectures and received marks.  

![wp-com-site-aboutme][2150]  

### DONATIONS page
The donations page contains a summary about me and gives visitors the choice to support my work.  

![wp-com-site-donations][2160]  

# Building your website 

## Step by step tutorial

### WordPress.com, Step 1: register
By choosing WordPress.com you can register for a free or a paid plan. That's it, no need to install WordPress, PHP, Nginx web-server, MySQL or anti-hacker-software. That's part of WordPress.com's service. If you choose a free plan, there are certain constraints or limitations, though.   
  
Main constraints of a free plan are: 
* Mainly for security reasons, the number of themes you can choose from. 
* You can't define own CSS classes to style your webpage.
* The way you can monetize your website.
* To finance themselves, WordPress.com places adds on your website.
* You can't install plugins.

The first image below shows WordPress.com's website, where you can register for a free account. The second image shows the main administration screen of WordPress.com. From there, you can build your website or upgrade to another plan. This administration screen differs slightly from the one of the open source version of WordPress.org and might further change in the future. 

![wp-com-register][1030]  
![wp-com-admin][1010]  

### WordPress.com, further steps to build your website similar to WordPress.org
Because at WordPress.com you can also access the administration screen of the open source version of WordPress.org, I only show the screenshots of the open source version. In the end it doesn't matter, which administration screen you use or which link you click, in order to build your website. To access the administration screen of WordPress.org you add `/wp-admin/` to the administration screen of your WordPress.com URL.

### WordPress.org, Step 1: register and install
By choosing WordPress.org you are downloading the open source version of WordPress. First, you have to register for a domain name and a place to host your website. Prices for these services have come down rapidly, but still, I am not aware of a provider, that offers a free plan for them. After that you will be provided with your URL and your user account, from where you can build your website. Depending on, which service provider you choose, you probably have to install your own WordPress.org, PHP, Nginx web-server, MySQL or anti-hacker-software. These are the downsides of WordPress.org with respect to WordPress.com, but there are also a few important advantages.

Main advantages of WordPress.org over WordPress.com:
* You can install any theme, you can even build your own themes
* You can monetize your website in any way you like
* No third party ads are place on your website
* You can install any plugin you like


### WordPress.org and Wordpress.com, Step 2: Choose your theme
Choose Appearance and Themes to choose your theme, I checked many and in the end decided to activate Lodestar. Depending on what theme you chose, you have more or less options and features available.  

![wp-admin Appearance Theme][30]  

### WordPress.org and Wordpress.com, Step 3: Customize your theme
Choose Appearance and Customize to start the Customizer. In the end you will have to click through each section in order to customize your website. 

![wp-admin Appearance Customize][10]  

The first and most important part is to choose the menus section to enter your menu or navigation tabs of your website and link them to your webpages, which you will create next.

![wp-admin Appearance Customize Menu][20]  

### WordPress.org and Wordpress.com, Step 4: Create your pages
Below, you see my webpages. The Front Page, which is my HOME page and the Posts page are standard concepts in WordPress.org. This is not the case for the Portfolio / Projects page and the Testimonials page, which are only supported by certain themes, like e.g. Lodestar. 

As you can see, I also added three additional pages, Donations, About me and another one, I never published. 

By clicking the Add New button, you can add a new webpage. Once created it shows in the list and can be accessed by clicking the corresponding list entry. 

![wp-admin Pages][70] 


By clicking the Front page link, you can enter the Front or HOME page. 

![wp-admin Pages Page][80]  

By clicking the Add New button, you can enter an empty page. First, you should give it a title. After that, you can start filling the page with content. WordPress offers blocks, which automatically add HTML tags around your content. The image below shows the available block categories. Each category offers blocks, from which you can choose. 
![wp-admin Pages Page BlockCategories][90]   

The Most Used Block Types dropdown window contains the blocks types, you most often used in the past. It is accessed by clicking the plus sign.   
![wp-admin Pages Page MostUsedBlockTypes][110]  
![wp-admin Pages Page MostUsedBlockTypes][110]  

To enter a title you can choose the Heading block type, to enter text you can choose the Paragraph block type, to add an image you can choose the image block type, and so on.
![wp-admin Pages Page Blocks][100] 

In order to embed a YouTube video you have several possibilities. But if you like to give the window a fixed size and to center align it, in WordPress.org you have to enter HTML code similar to what is shown in the image below.
![wp-admin Pages Page YouTubeVideo][120]  

The same is true for YouTube videos in WordPress.com, but the HTML code is different.
![wp-com Page YouTubeVideo][1020]  

Whenever you want to add an image or a video you can either upload it to WordPress or to another hosting site. To upload images or videos you can drag and drop them into the Media Library, which you can access over the navigation bar as shown below or directly over a link in some blocks. 
![wp-admin Media][60]

#### Important note
Do not upload big videos to WordPress if you expext a lot of traffic to your webpage. Host them e.g. on YouTube. The same is true for webpages with lots of big images. Most hosting plans for websites have traffic limitations. If you host your video on Youtube, your website hosting is unaffected by this traffic.

### WordPress.org and Wordpress.com, Step 5: Create your posts
The whole process for posts is similar to the one for pages. Below, you see the list of my blog posts.  

By clicking the Add New button, you can add a new blog post. Once created it shows in the list and can be accessed by clicking the corresponding list entry. 

![wp-admin Posts][150]  

![wp-admin Posts Post][160]  

### WordPress.org and Wordpress.com, Step 6: Create your portfolio / projects
Again the whole process for projects is similar to the one for pages. Below, you see the list of my projects.  

By clicking the Add New button, you can add a new project. Once created it shows in the list and can be accessed by clicking the corresponding list entry. 

![wp-admin Portfolio][130]  

![wp-admin Portfolio Projects][140]  

### WordPress.org and Wordpress.com, Step 7: Create your testimonials
And again the whole process for testimonials is similar to the one for pages. Below, you see the list of my testimonials.  

By clicking the Add New button, you can add a new testimonial. Once created it shows in the list and can be accessed by clicking the corresponding list entry. 

![wp-admin Testimonials][200]  

![wp-admin Testimonials Testimonial][210]   

### WordPress.org and Wordpress.com, Step 4: customize the settings
![wp-admin Settings Backup][170]  
![wp-admin Settings Reading][180]  
![wp-admin Settings Writing][190]  

### WordPress.org and Wordpress.com, Step 4: Create your pages
![wp-admin Comments][40]  
![wp-admin Jetpack][50]  

---------------
qoolixiloop, 20. Mar. 2019

[10]: wordpress.org/images/wp-admin_Appearance_Customize.jpg
[20]: wordpress.org/images/wp-admin_Appearance_Customize_Menus.jpg
[30]: wordpress.org/images/wp-admin_Appearance_Theme.jpg
[40]: wordpress.org/images/wp-admin_Comments.jpg
[50]: wordpress.org/images/wp-admin_Jetpack.jpg
[60]: wordpress.org/images/wp-admin_Media.jpg
[70]: wordpress.org/images/wp-admin_Pages.jpg
[80]: wordpress.org/images/wp-admin_Pages_Page.jpg
[90]: wordpress.org/images/wp-admin_Pages_Page_BlockCategories.jpg
[100]: wordpress.org/images/wp-admin_Pages_Page_Blocks.jpg
[110]: wordpress.org/images/wp-admin_Pages_Page_MostUsedBlockTypes.jpg
[120]: wordpress.org/images/wp-admin_Pages_Page_YouTubeVideo.jpg
[130]: wordpress.org/images/wp-admin_Portfolio.jpg
[140]: wordpress.org/images/wp-admin_Portfolio_Projects.jpg
[150]: wordpress.org/images/wp-admin_Posts.jpg
[160]: wordpress.org/images/wp-admin_Posts_Post.jpg
[170]: wordpress.org/images/wp-admin_Settings_Backup.jpg
[180]: wordpress.org/images/wp-admin_Settings_Reading.jpg
[190]: wordpress.org/images/wp-admin_Settings_Writing.jpg
[200]: wordpress.org/images/wp-admin_Testimonials.jpg
[210]: wordpress.org/images/wp-admin_Testimonials_Testimonial.jpg
[1010]: wordpress.com/images/wp-com-admin.jpg
[1020]: wordpress.com/images/wp-com_Page_YouTubeVideo.jpg
[1030]: wordpress.com/images/wp-com-register.jpg
[1010]: wordpress.com/images/wp-com-admin.jpg
[1020]: wordpress.com/images/wp-com_Page_YouTubeVideo.jpg
[1030]: wordpress.com/images/wp-com-register.jpg
[2010]: wordpress.com/images/wp-com-site-home1.jpg
[2020]: wordpress.com/images/wp-com-site-home2.jpg
[2030]: wordpress.com/images/wp-com-site-home3.jpg
[2040]: wordpress.com/images/wp-com-site-home4.jpg
[2050]: wordpress.com/images/wp-com-site-home5.jpg
[2060]: wordpress.com/images/wp-com-site-home6.jpg
[2070]: wordpress.com/images/wp-com-site-home7.jpg
[2080]: wordpress.com/images/wp-com-site-posts.jpg
[2090]: wordpress.com/images/wp-com-site-posts-post.jpg
[2110]: wordpress.com/images/wp-com-site-projects.jpg
[2120]: wordpress.com/images/wp-com-site-projects-project1.jpg
[2130]: wordpress.com/images/wp-com-site-projects-project2.jpg
[2140]: wordpress.com/images/wp-com-site-testimonials.jpg
[2150]: wordpress.com/images/wp-com-site-aboutme.jpg
[2160]: wordpress.com/images/wp-com-site-donations.jpg

 
