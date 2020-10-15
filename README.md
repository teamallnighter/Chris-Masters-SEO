# Chris Masters SEO

Notes from an online [course](https://www.udemy.com/course/learn-seo) that I took on SEO

[PDF](https://github.com/teamallnighter/Chris-Masters-SEO/blob/main/seo.pdf)

[You Tube Video From Google](https://www.youtube.com/watch?v=BNHR6IQJGZs)

## Crawl Friendliness

__when checking google use igncognito mode__

### Keep important content in plain HTML

* Dont use JS for content you want crawled
* Don't use images with keywords

## Use Images 

* Name images with your keyword 
* Use ALT text with keyword

** Keep your site mobile friendly

 __Google uses a mobile crawler__

 __Use a responsive site and not seperate URLS__

 ### Testing Speed

 [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights)

 [Webpagetest.org](https://webpagetest.org/easy.php)

 [https://gtmetrix.com/](https://gtmetrix.com/)

 ### Testing Mobile Friendliness

 [Google](https://search.google.com/test/mobile-friendly)

 ## Crawl Budget

 __Avoid duplicate pictures__

 Use a /filter file for duplicates. Use robots.txt to avoid this folder

 ## Choosing Domains 

 * Dont use spammy on domains 
 * '-' look spammy
 * dont use .biz
 * Small boost to having keyword in the domain (not worth it)

 [https://www.spamhaus.org/statistics/tlds/](https://www.spamhaus.org/statistics/tlds/)

 ## Setting up architecture 

 * Keep similar content on same sub domains
 * Keep important pages on the top level domain
 * Google assumes the deeper into directories the file it is the less important it is
 * Avoid random strings in URL
 * Use pretty url 

 ### Internal Strings

* Use simple A links
* Anchor text important
* Use descriptive anchor tags

## Key Words 

### Choosing Keywords 

* Should be relevant to your objective
* attract targeted audience 
* look into search volume 
* Check out competition
* Backlinks still matter

#### Keyword Tools 

##### Free 

[Google Keyword Planner](https://ads.google.com/intl/en_ca/getstarted/?subid=ca-en-ha-awa-bk-c-000!o3~CjwKCAjw5p_8BRBUEiwAPpJO67Ht_qp8FRkxEL92uZ7fNcyOa6Tz4PysrDbPo2olv2eQbTsvVKM2dxoC-WMQAvD_BwE~76351061926~kwd-58879037234~6466339605~445459180200&gclid=CjwKCAjw5p_8BRBUEiwAPpJO67Ht_qp8FRkxEL92uZ7fNcyOa6Tz4PysrDbPo2olv2eQbTsvVKM2dxoC-WMQAvD_BwE)

[Keywords everywhere chrome/firefox extension](https://chrome.google.com/webstore/detail/keywords-everywhere-keywo/hbapdpeemoojbophdfndmlgdhppljgmp?hl=en)

##### Paid 

[moz](https://moz.com/moz-pro-free-trial?utm_medium=cpc&utm_source=google&utm_campaign=Brand%20-%20Exact%20|%20NA&utm_adgroup=Brand%20-%20Exact%20-%20Moz&utm_term=moz&gclid=CjwKCAjw5p_8BRBUEiwAPpJO66Y4X71pKAmSfELcIQup4i4cz4N-i469cLp2ZLMv7eM07PnM3R4l0hoCBIsQAvD_BwE)

[Ahrefs](https://ahrefs.com/)

## Page Templates 

### Title Tage

__The most important on page SEO factor__

* Should indicate the main topic of the document
* Shows on browsere tab and search engine results page
* __Include the keyword at the beginning of the title tag__
* Keep within 50 characters
* Entice Clicks 
* Avoid dupliciates 

### Heading Tags 

Indicate the heading of the content 

* __Use one <h1> the contains the targeted key word or variation__
* Use <h2> for subheadings and include targeted keywords or support keywords

### Body Text 

* Include variations of keywords where it looks natural 
* Dont over optimize
* Make it human readable first
* Have unique content 

### Meta Description

* Provides a preview of the page
* NOT direct SEO factor 
* __Make it enticing__ 
* If you use a keyword it will be bolded
* Use around 165 characters 

```html
<head>
<meta name="description" content="I am the description. Make me enticing and around 165 characters. If you use your keyword it will be bolded>
</head>
```

### Semantic HTML

* Use <section> <header> <article> <footer>

[W3 Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)

## Structured Data 

* Produces attractive search results for text based search
* Helps Search engines understand what the content is
* Great for non text based searches like Alexa

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Recipe",
  "author": "John Smith",
  "cookTime": "PT1H",
  "datePublished": "2009-05-08",
  "description": "This classic banana bread recipe comes from my mom -- the walnuts add a nice texture and flavor to the banana bread.",
  "image": "bananabread.jpg",
  "recipeIngredient": [
    "3 or 4 ripe bananas, smashed",
    "1 egg",
    "3/4 cup of sugar"
  ],
  "interactionStatistic": {
    "@type": "InteractionCounter",
    "interactionType": "https://schema.org/Comment",
    "userInteractionCount": "140"
  },
  "name": "Mom's World Famous Banana Bread",
  "nutrition": {
    "@type": "NutritionInformation",
    "calories": "240 calories",
    "fatContent": "9 grams fat"
  },
  "prepTime": "PT15M",
  "recipeInstructions": "Preheat the oven to 350 degrees. Mix in the ingredients in a bowl. Add the flour last. Pour the mixture into a loaf pan and bake for one hour.",
  "recipeYield": "1 loaf",
  "suitableForDiet": "https://schema.org/LowFatDiet"
}
</script>
```

[json-ld.org](https://json-ld.org)

[Json-ld Playground](https://json-ld.org/playground)

