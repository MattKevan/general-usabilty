---
title: "Making WSJ.com more accessible"
date: 2016-08-03 00:00:00 +0000
dateadded: 2021-03-11 15:43:17 +0000
description: ""
link: "https://matthewstrom.com/writing/wsj-accessibility/"
category:
directory:
- _directory/matthew-ström.md
---
<p>As I write this, the WSJ.com team is launching a brand new homepage experience for small screens.<sup class="footnote-ref"><a href="#fn1" id="fnref1">1</a></sup> It’s one of our biggest subscription-drivers, a page that hundreds of thousands of people see every day. The new experience builds on the award-winning design of the WSJ iOS and Android apps. It’s curated specifically for mobile reading by an amazing editorial team.</p>
<p>It’s also our first step towards making WSJ.com more accessible to all of our users.</p>
<figure data-type="image"><img src="https://matthewstrom.com/images/accessibility-2.jpg" alt="The WSJ.com mobile homepage before and after the re-design"><figcaption>The WSJ.com mobile homepage before and after the re-design</figcaption></figure>
<p>For many products — especially media platforms — accessibility is a bullet point on a QA checklist. I want to set a much higher bar for our products. Over the past 6 months, I’ve collaborated closely with designers, product managers, engineers, and journalists to focus on <strong>leading the media industry in accessibility standards.</strong> The new mobile homepage is proof of our team’s dedication to that mission.</p>
<p>As we continue our pursuit of accessibility across all of WSJ.com, I’d like to share the work we’ve done to get here.</p>
<h2 id="defining-accessibility">Defining accessibility</h2>
<p>Last November, I set out to write accessibility guidelines for the WSJ.com team. I wanted to tackle the hardest question first: what does accessibility mean? After lots of writing and editing, I had the following:</p>
<div style="background: rgba(255, 255, 0, 0.1); padding: 0.5em 1em; margin-bottom: 1em">
<h3 id="what-is-accessibility%3F">What is accessibility?</h3>
<p><strong>Accessibility</strong> is the word we use when describing a broad set of guidelines and principles that make our products <em>easy to use.</em></p>
<h3 id="why-is-accessibility-important%3F">Why is accessibility important?</h3>
<p>Many of our members have visual, hearing, motor, or cognitive disabilities. It is our goal to provide the same value to them as any other member.</p>
<p>However, <strong>accessibility is for everybody.</strong> Here are some examples of <em>situational</em> disabilities:</p>
<ul>
<li>Visual: Reading a story outside in bright sunlight that makes it difficult to read small text</li>
<li>Hearing: Watching a video in a loud place that makes it difficult to hear audio</li>
<li>Motor: Wearing winter gloves that make it difficult to use a touchscreen accurately</li>
<li>Cognitive: Listening to a podcast while cooking, making it difficult to pay attention</li>
</ul>
<p>By adhering to and maintaining these principles and guidelines, we can make our products better for all our users.</p>
</div>
<p>Defining accessibility this way helps us understand just how vital it is to our products. You can read a public version of our guidelines <a href="https://matthewstrom.com/pages/wsj-accessibility-guidelines" target="_blank" rel="noopener">here</a>.</p>
<h2 id="partnering-with-engineering">Partnering with engineering</h2>
<p>Designing for accessibility is only one part of the process.  <em>Building accessible products</em> requires a close collaboration between engineers and designers.</p>
<p>For example, many of our users navigate the site without a mouse. Instead, they use a keyboard, joystick, or sip and puff technology. To these users, <strong>focus states</strong> are vital — imagine using a mouse without an onscreen pointer! Our designers specified meaningful focus states for all elements (not just buttons), and engineering ensured focus states are always present<sup class="footnote-ref"><a href="#fn2" id="fnref2">2</a></sup>. During the build and QA phases, automated tests make sure we didn’t miss anything. Close collaboration allows us to build things the right way.</p>
<h2 id="advocating-for-accessibility">Advocating for accessibility</h2>
<p>In addition to pursuing collaboration with engineering, it’s important to communicate the importance of accessibility to your stakeholders. These stakeholders can be leaders inside your company, groups of users, or valuable contributors outside the organization.</p>
<p>On the WSJ design team, we use <a href="https://matthewstrom.com/writing/principles.html" target="_blank" rel="noopener">design principles</a> to communicate our values. At the time I’m writing this, two of our six principles address accessibility:</p>
<blockquote>
<p><strong>Enable Users</strong><br>
Everything that we design should enable users to access, connect with, and contribute to the content produced by The Wall Street Journal.</p>
</blockquote>
<blockquote>
<p><strong>Design for Everybody</strong><br>
Apply accessibility and inclusivity principles at every step of the process. Design not only for the users we have today, but for the users we want to have in the future.</p>
</blockquote>
<p>By publishing and sharing these principles, we help others see the value of accessibility in the same way we do.</p>
<h2 id="the-result">The result</h2>
<p>Our work has paid off. The previous mobile homepage scored an embarrassing 39 points on Google’s Lighthouse accessibility audit.</p>
<figure data-type="image"><img src="https://matthewstrom.com/images/accessibility-3.png" alt="Google Lighthouse accessibility audit on May 20th, 2018"><figcaption>Google Lighthouse accessibility audit on May 20th, 2018</figcaption></figure>
<p>At this moment, our new mobile homepage is at an <strong>82</strong> 🎉 <sup class="footnote-ref"><a href="#fn3" id="fnref3">3</a></sup></p>
<figure data-type="image"><img src="https://matthewstrom.com/images/accessibility-4.png" alt="Google Lighthouse accessibility audit on June 3rd, 2018"><figcaption>Google Lighthouse accessibility audit on June 3rd, 2018</figcaption></figure>
<p>We still have some work to do on this page to push the score even higher. Getting a score of 100 isn’t our goal, however, and we’ll never be able to ace every metric of accessibility. Instead, as we continue on to other parts of WSJ.com, I’m keeping a simpler mission in mind: make our products easy to use for everybody.</p>
<h4 id="acknowledgements">Acknowledgements</h4>
<p>Everything we do at The Wall Street Journal is a collaboration. I want to give a special thanks to Ryan Yun, who really made accessibility a priority in building this page. Many more people contributed, and continue to contribute, to this project and many others:</p>
<ul>
<li>Delia, product manager for WSJ.com’s core curation products</li>
<li>Our WSJ.com frontend team - Vishaal, Morgan, Vasudha, Adam, Christian, Surya, Doug, and Tania</li>
<li>The mobile team, including Jason, Mike, Janit, Amit, and Jordan.</li>
<li>Our editorial partners - Jenn, Lydia, and Meg</li>
<li>My design leadership peers, Bonnie, Thomas, and Fernando</li>
<li>The SEO and Revenue team - Rich, Chris, Gio, Johnny, Lee, Bhupendra, Marcin, Dominique, Anna, and Marish</li>
<li>Our product leadership, Katharine, Rajiv, and Che</li>
</ul>
<hr>
<section class="footnotes l--space-compact">
<div class="t--weight-bold l--pad-btm-s">Footnotes & References</div>
<ol class="footnotes-list">
<li id="fn1" class="footnote-item"><p>Update: we’re live! Visit <a href="https://wsj.com/" target="_blank" rel="noopener">https://wsj.com</a> on your phone to see the result of our hard work. <a href="#fnref1" class="footnote-backref">↩︎</a></p>
</li>
<li id="fn2" class="footnote-item"><p>My advice is to simply leave default focus states intact as much as possible. <a href="https://a11yproject.com/posts/never-remove-css-outlines/" target="_blank" rel="noopener">Here’s some more advice</a> from the a11y project. <a href="#fnref2" class="footnote-backref">↩︎</a></p>
</li>
<li id="fn3" class="footnote-item"><p>With a product as dynamic as WSJ.com, our accessibility scores fluctuate constantly. One of the biggest challenges we face is maintaining a high standard, regardless of our ever-evolving editorial and advertising strategies. <a href="#fnref3" class="footnote-backref">↩︎</a></p>
</li>
</ol>
</section>
