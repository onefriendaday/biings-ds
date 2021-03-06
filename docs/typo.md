<h6 class="subtitle is-6 is-uppercase has-text-grey">Foundation</h6><h1 class="title is-1 is-family-secondary">Typography</h1>
<hr class="is-visible is-size-3">
<p class="subtitle is-5 is-family-secondary">
    Use <strong>typography</strong> to create clear hierarchies to guide users through the product and experience. It is the core structure of any well designed interface.
</p>
<hr class="is-visible is-size-3"><br>

<h4 class="title is-3 is-family-primary">Font family</h4>

<ul class="list">
    <li>For maximum legibility Biings DS uses <span class="is-family-primary has-text-weight-medium">Averta</span> as its main font family.</li>
    <li>For important headings use <strong class="is-family-secondary has-text-weight-bold">Merriweather</strong> – modifier <code>is-family-secondary</code></li>
    <li>When a Monospace font is required use <strong class="is-family-monospace">Roboto Mono</strong> – modifier <code>is-family-monospace</code></li>
</ul>

!> Any text immediatly following a <span class="is-family-secondary">Merriweather</span> header should <span style="text-decoration: underline;">always</span> use <span class="has-text-weight-bold">Averta</span>.

<hr class="is-size-1 is-visible">
<h4 class="title is-3 is-spaced is-family-primary">Font weights</h4>
<p class="subtitle is-6">Use font weights to emphasize or differentiate content hierarchy.<br>Example: <code>has-text-weight-semibold</code></p>

<ul class="list is-size-5">
    <li><span class="has-text-weight-light">300 — Light</span></li>
    <li><span class="has-text-weight-normal">400 — Normal / <span class="is-family-secondary">Light Serif</span></span></li>
    <li><span class="has-text-weight-medium">500 — Medium / <span class="is-family-secondary">Medium Serif</span></span></li>
    <li><span class="has-text-weight-semibold">600 — Semibold / <span class="is-family-secondary">Semibold Serif</span></span></li>
    <li><span class="has-text-weight-bold">800 — Bold</span></li>
    <li><span class="has-text-weight-bolder">900 — Bolder / <span class="is-family-secondary">Bolder Serif</span></span></li>
</ul>

<hr class="is-size-1 is-visible">
<h4 class="title is-3 is-spaced is-family-primary">Scales</h4>
<p class="subtitle is-6">
Titles and subtitles have sizes ranging from 1 (biggest) to 6 (smallest). 
Texts have an extra 7th smaller size. Use the modifier syntax <code>is-[0-6]</code> for titles, and <code>is-size-[0-8]</code> for texts.
</p>

?> There should be a size difference of <strong>2</strong> between a title and its direct subtitle.

<hr>

<h1 class="title is-0 is-family-secondary">Title Zero</h1><div class="subtitle is-4 has-text-grey">Viewport proportional header</div>
<hr class="is-smaller">
<h1 class="title is-1 is-family-secondary">Title One</h1><div class="subtitle is-4 has-text-grey">Main page header</div>
<hr class="is-smaller">
<h2 class="title is-2 is-family-secondary">Title Two</h2><div class="subtitle is-4 has-text-grey">Section title</div>
<hr class="is-smaller">
<h3 class="title is-3 is-family-secondary">Title Three</h3><div class="subtitle is-5 has-text-grey">Default title</div>
<hr class="is-smaller">
<h4 class="title is-3 is-family-secondary">Title Four</h4><div class="subtitle is-6 has-text-grey">Large paragraph</div>
<hr class="is-smaller">
<h5 class="title is-5 is-family-secondary">Title Five</h5><div class="subtitle is-6 has-text-grey">Paragraph</div>
<hr class="is-smaller">
<h6 class="title is-6 is-family-secondary">Title Six</h6><div class="subtitle is-6 has-text-grey">Same size as regular text</div>

<hr class="is-size-1 is-visible">
<h4 class="title is-3 is-spaced is-family-primary">Emphasizers</h4>
<p class="subtitle is-6">
Use one of the following classes to emphasize words or part of a text.
</p>

<hr class="is-small">

<div class="box is-well is-marginless is-size-5">
    Let's <u>underline that!</u>
</div>

    Let's <u>underline that!</u>
<hr class="is-small">

<div class="level is-marginless is-size-5 has-background-white-bis">
    <div class="level-item is-marginless">
        <div class="box is-large">
            And let's<em> highlight this part </em>..
        </div>
    </div>
    <div class="level-item is-large is-marginless">
        <div class="box is-large has-background-black-ter has-text-white">
            Or <em class="is-primary">that on a dark background</em>.
        </div>
    </div>
</div>
    
    And let's <em>highlight this in yellow</em>..
    Or <em class="is-primary">some of that in purple</em>.
<hr class="is-small">

<div class="box is-well is-marginless is-size-5">
    <p class="is-italic">Lorem ipsum dolor sit amet.<p>
</div>

    <p class="is-italic">Lorem ipsum dolor sit amet.<p>
<hr class="is-small">

<div class="box is-well is-marginless is-size-5">
    <p class="is-capitalized">this is capitalized</p>
</div>

    <p class="is-capitalized">this is capitalized</p>
<hr>

<a href="http://bulma.io/documentation/modifiers/typography-helpers/" target="blank" class="box is-bordered is-link">
    More information on &nbsp;→&nbsp; <span class="has-text-primary">Bulma / <strong>Typography helpers</strong></span>
</a>
