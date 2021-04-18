# Refractoring-Horiseon

## Description

Horiseon tasked us with adding accessability features to their site to improve the user experience for all users, and to increase search engine optomization. Using code provided, general div classes were specified with semantic tags and alt tags we added to image sources. A link was also fixed in the HTML. In the CSS different rules were consolidated to save space and make a more easy to follow stylesheet. A full list of changes is provided below.

List of changes to HTML:
/* removed header class in place of semantic tag */ 
/* added semantic tag 'main' to separate layout further */  
/* changed div class to semantic tag 'section' */  
/* changed div class to semantic tag 'article' */   
/* added article id to fix link */  
/* created alt tags for accessability */    
/* removed footer class in place of semantic tag */     

List of changes to CSS:
/* removed header class selector to just header tag */  
/* changed from class .header h1 selector to just header h1 tag */  
/* changed from class .header .seo selector to just header .seo tag */  
/* changed from class .header div selector to just header div tag */    
/* changed from class .header div ul selector to just header div ul tag */  
/* changed from class .header div ul li selector to just header div ul li tag */     
/* consolidated .float-left, and .float-right css rules */  
/* consolidated .benefit-lead, .benefit-brand, and .benefit-cost css rules */    
/* consolidated .benefit-lead h3, .benefit-brand h3, and .benefit-cost h3 css rules */  
/* consolidated .benefit-lead img, .benefit-brand img, and .benefit-cost img css rules */   
/* consolidated .search-engine-optimization, .online-reputation-management, and .social-media-marketing css rules */    
/* consolidated .search-engine-optimization img, .online-reputation-management img, and .social-media-marketing img css rules */    
/* consolidated .search-engine-optimization h2, .online-reputation-management h2, and .social-media-marketing h2 css rules */   
/* removed footer class selector to just footer tag */     

MIT License

Copyright (c) [2021] [Scott Siegel]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.