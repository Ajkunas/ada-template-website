
_Brewing the perfect beer is a task many set out for and only a few, if any, even achieve. When it comes to crafting a beer, choosing the right ingredients, temperature, brewing equipment and overall recipe design is crucial while leading to an explosion of possibilities. It is this vastness of possibilities that captivates so many brewers around the globe chasing the perfect beer. With our project we aim to break the flood of information supplied by the beer rating websites BeerAdvocate and RateBeer down into easily digestible pieces of information, leading to meaningful insight for interested readers and might even increase their chances of brewing a well liked beer._

**Do you prefer to stick to the same three popular types of beer that you know, or would you be ready to immerge yourself into the world of beers and discover a choice that perfectly matches the mood of the month ?**

To do so, we will analyze the volume of alcohol, the location of breweries and the aroma, taste, appearance and palate ratings for each month. Our goal is to extract the best combinations for each month to recommend a consumer and/or brewery the most **popular** combination ! 
Our analysis is monstly based on time series analysis coupled with statistical tests and keywords analysis. 

Let's go together on the road to the **perfect** beer ! 

# 🍻 First step to the perfect beer: Our focus 🍻

Before beggining to analyze the attributes, we need to determine our focus on consumers and state our assumptions. 

## Who are our consumers ? 

It is important to observe the provenance of the raters in the datasets. Since we focus on an analysis per month, depending on the location of the users and their lifestyle, it might change considerably when they come from different parts of the world.

{% include number_of_users_per_country.html  %}

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
