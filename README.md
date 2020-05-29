# nateptay.github.io

## js-library criteria evaluation

**Primary Library:** AOS (Animate On Scroll)

**Comparison Library:** ScrollMagic

### Usability:
**AOS:** AOS has a variety of options for animating elements when a user scrolls. This can create a cool effect that helps draw users in.

**ScrollMagic:** ScrollMagic has a lot of functionality for creating interesting scroll actions. It allows both horizontal and vertical scrolling, which can be engaging to users that are used to only vertical scrolling.

### Download Size:
**AOS:** 84.5KB Zip Download

**ScrollMagic:** 1,513 KB Zip Download

### Dependencies:
**AOS:** None

**ScrollMagic:** None

### Functionality/Reusability:
**AOS:** This library is able to be implemented directly in the HTML file, and allows you to animate objects by adding individual tags to the element you want animated. It's easy to get used to, and it works well with pre-existing styling.

**ScrollMagic:** This library is set up to have a controller with scenes attached to it. There is one controller for each scroll area, and there can be multiple scroll areas per webpage. The setup is a little more complicated because you need to reference html elements from the scenes, and attach the scenes to the correct controllers. There are tutorials on the github page to help walk you through the setup.

### Robust:
**AOS:** This works in modern browsers, as well as older browsers that support css animations.

**ScrollMagic:** This currently works in Firefox 26+, Chrome 30+, Safari 5.1+, Opera 10+, and IE 9+, with the goal of supporting older versions of major browsers as well.

### Performance:
**AOS:** This mostly uses CSS, so it doesn't cause many performance issues at all.

**ScrollMagic:** This is a lightweight program that doesn't cause many performance issues at all.

### Maturity:
**AOS:** 41 releases since 2015. It hasn't been updated since 2018, so it might not be developing anymore.

**ScrollMagic:** 28 releases since 2013. It hasn't been updated since 2019, but it does look like they are still working on adding browser compatibility with Zombie browsers.

### Ongoing Development:
**AOS:** This is an open source project available on github. The last update by any of the 18 contributors to this package was in 2018, but there are still many pull requests that have been made this year. 

**ScrollMagic:** This is an open source project available on github. It has 30 contributors, and the latest update was in 2019. The documentation states that ScrollMagic aims to support all major browsers even in older versions, and currently supports Firefox 26+, Chrome 30+, Safari 5.1+, Opera 10+, and IE 9+

### Licensing:
**AOS:** MIT License

**ScrollMagic:** MIT License and General Public License

### Supportive Community:
**AOS:** Has many articles, reviews, and recommendations. The Stack Overfow questions mostly have at least one response.

**ScrollMagic:** Offers personal live support. There are plenty of questions being asked about it in StackOverflow, but there isn't much interaction with the posts.

### Documentation Quality 
**AOS:** Has documentation for installation and use, and demos that show examples of the library's code with the function of the code.

**ScrollMagic:** Has a wiki, clear documentation, a troubleshooting guide. The demo page shows a couple of features hidden throughout, but they weren't highlighted as much or as clearly as the ones on the AOS page.

### Developer Options:
**AOS:** Works with Package Managers to download and install. It works well with other packages and styling, which is good for expanding webpages beyond fancy scrolling.

**ScrollMagic:** Plugin-based architecture is designed to be extended and customized as long as the user knows what they're doing. Works well with other plugins like GSAP or VelocityJS. 
