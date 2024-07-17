<div class="hero">
    <h1 class="hero-title">Unveiling the Story Behind the Numbers!<br/></h1>
    <p class="hero-description">Welcome to our data story, where numbers come alive and reveal the hidden narratives shaping our world. Here, we don't just present data; we transform it into compelling stories that are both insightful and impactful.</p>
</div>


# Hello

![[Hello.png]]

*(Photo by Kassandra O'Shea on [flicker](http://www.flickr.com/photos/kyabean/8194627569/))*

## Discover the Power of Data

In this data-driven journey, you'll explore:
- Hidden Patterns: Uncover the trends and patterns that lie beneath the surface of raw data.
- Interactive Visuals: Engage with dynamic charts, graphs, and infographics that make complex information accessible and understandable.
- Real-World Impacts: See how data influences our daily lives, drives decision-making, and shapes the future.
- Expert Insights: Benefit from in-depth analysis and commentary from leading data scientists and industry experts.

## Okay, I published the template. Now what?

You can add as many markdown files to your GitHub repository as you like, and you can freely nest them in subdirectories. You can also enhance your content with data visualisation components and markdown features.

> Note: For a full list of supported markdown features visit [Markdown syntax support](https://datahub.io/@olayway/docs/Markdown%20syntax%20support)

### How to take this template to the next level

<div class="middle-button-container">
    <a href="https://datahub.io/@olayway/docs/Publish%20data-rich%20stories" class="middle-button">How to publish data-rich stories</a>
</div>

<div class="middle-button-container">
    <a href="https://datahub.io/@olayway/docs/Customize%20Your%20DataHub%20Cloud%20Site%20with%20CSS" class="middle-button">Customize your site with CSS and HTML</a>
</div>

<div class="middle-button-container">
    <a href="https://datahub.io/@olayway/docs/Add%20visuals%20and%20data-rich%20components" class="middle-button">Add visuals and data-rich components</a>
</div>

<div class="middle-button-container">
    <a href="https://datahub.io/@olayway/docs/Add%20sidebar%20navigation" class="middle-button">Add sidebar navigation</a>
</div>

<div class="middle-button-container">
    <a href="https://datahub.io/@olayway/docs/Configuring%20Nav%20bar%20and%20SEO%20fields" class="middle-button">How to Configure Basic SEO Fields and Nav Bar</a>
</div>

> [!important]
> I am saying something important here!

> [!warning]
> Just testing some callout blocks here.

> [!done]
> Test passed.

## Testing data-rich components

I will add a data table from my data.csv file below:
<FlatUiTable
  data={{
    url: 'data.csv'
  }}
 />

 Looks kinda cool. What about a linechart? Let's see what this would look like:

 <LineChart
  data={{
    url: 'data.csv'
  }}
  title="C02 PPM per decade"
  xAxis="year"
  yAxis="co2"
/>

If you want to explore more of what's possible:

<div class="middle-button-container">
    <a href="https://datahub.io/@olayway/docs" class="middle-button">Go to the docs</a>
</div>

