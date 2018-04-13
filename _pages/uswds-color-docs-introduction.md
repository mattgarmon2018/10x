---
layout: prototype-clean
title: USWDS color
permalink: /uswds-color-docs-introduction/
---

<div class="font-mono-f4 font-weight-300 padding-top-base padding-bottom-double tablet:padding-top-double tablet:padding-bottom-triple background-color-white-1">

  <div class="g-container-desktop margin-bottom-0 padding-x-double padding-top-base margin-top-0">
    <div class="g-row">
      <div class="g-col-8">
        <p class="font-sans-f4 color-black-50 margin-top-0 margin-bottom-base font-weight-400"><span class="color-black font-weight-800 padding-eighth border-eighth line-height-smallest padding-bottom-0 margin-right-half">USWDS</span> Docs <span class="color-black">/</span> Style <span class="color-black">/</span> Colors</p>
          <h1 class="font-sans-f14 font-weight-300 margin-top-0 line-height-smaller margin-bottom-0">An introduction to colors</h1>
      </div>
      <div class="g-col-4">
        <figure class="margin-0 display-block">
          <img class="max-width-full display-block margin-x-auto" src="{{ '/assets/img/uswds/geodesic-header.webp' | relative_url }}" alt="A geodesic dome with colorful nodes">
        </figure>
      </div>
    </div>

    <div class="g-row margin-top-0 border-top-pixel padding-top-base-plus">
      <div class="g-col-3 sidenav">
        <ul class="list-reset font-sans-f6 font-weight-700">
          <li class="padding-bottom-half"><a class="color-black-90 text-decoration-none hover:text-decoration-underline" href="{% link _pages/uswds-color-docs-introduction.md %}">Introduction</a>
            <ul class="list-reset font-weight-300 margin-top-half margin-bottom-base">
              <li>USWDS colors</li>
              <li>Color and accessibility</li>
              <li>USWDS color wheels</li>
              <li>General color guidelines</li>
              <li>Pairing colors</li>
              <li>References</li>
            </ul>
          </li>
          <li class="padding-bottom-half"><a class="color-black-90 text-decoration-none hover:text-decoration-underline" href="{% link _pages/uswds-color-docs-theme.md %}">Project theme palette</a></li>
          <li class="padding-bottom-half"><a class="color-black-90 text-decoration-none hover:text-decoration-underline" href="{% link _pages/uswds-color-docs-system.md %}">System palette</a></li>
          <li><a class="color-black-90 text-decoration-none hover:text-decoration-underline" href="{% link _pages/uswds-color-docs-system.md %}">Special palettes</a></li>
        </ul>
      </div>
      <div class="g-col usa-body-content padding-x-base-plus font-sans-f8">

        <!-- ###################################################### -->

        <p class="font-sans-f11 font-weight-300 line-height-base margin-top-0">Color is a pratical and emotional tool. It conveys personality, sets a tone, attracts the eye, and indicates importance.</p>

        <h2 class="font-sans-f10 margin-top-double margin-bottom-double border-top-pixel padding-top-base">USWDS colors</h2>

        <p>USWDS organizes its colors into two related palettes: the <strong><a href="#0">project theme palette</a></strong> and the <strong><a href="#0">system palette</a></strong>. The project theme palette is a subset of the broader system palette — your project’s theme should reflect your project’s individual identity, tone, and needs. It will use only a few color families from the broader set of 26 color families available to all users of the system.</p>
        <p>Use colors from the system palette for your project. In the long run, it’s a better user experience across government when there's coherence across sites and services. Or course, your project’s need come first, but if you plan to contribute your designs back into the system, those designs will need to conform to the system palette.</p>
        <aside class="background-color-white-warm-3 padding-base-plus margin-y-double border-radius-small font-weight-400 font-sans-f6">
          <h4 class="margin-top-0 text-transform-uppercase font-sans-f4 letter-spacing-loose margin-bottom-0">Color, color family, and grade</h4>
          <p class="font-weight-400 font-sans-f6 margin-top-half">Throughout our documentation and guidance, we’ll use use the terms <em>color</em>, <em>color family</em>, and <em>grade</em>, but what do we mean when we use them?</p>
          <p class="font-weight-400 font-sans-f6"><strong>Color</strong> is any specific swatch in our palettes, like <code>red-50</code>, <code>primary-base</code>, or <code>indigo-warm-60v</code>.</p>
          <p class="font-weight-400 font-sans-f6"><strong>Color family</strong> is a group of colors that all have the same hue on a color wheel (See <a href="#0">USWDS color wheels</a>, below.). They contain a number of individual colors, distinguished by the brightness or saturation of each individual color. A color family is typically a conventional color name like <code>Red</code> or <code>Blue warm</code>, or could be a use-based name in the theme palette, like <code>Primary</code>. </p>
          <p class="font-weight-400 font-sans-f6"><strong>Grade</strong> is a way to express the value or lightness of a color: how light or dark a color is. USWDS uses <a href="#0">a 100-point scale</a> to communicate the grade, where 0 is pure white and 100 is pure black. We’ve regularized these grades across color families: a color of grade <code>50</code> in one color family should be the same level of brightness as a color of grade <code>50</code> in another color family. This has important color contrast and accessibility implications that we’ll discuss <a href="#0">later</a>.</p>
        </aside>

        <h2 class="font-sans-f10 margin-top-double margin-bottom-double border-top-pixel padding-top-base">Color and accessibility</h2>

        <p>Accessibility is not a special case.</p>
        <p>Color is powerful, but its effects are neither completely predictable nor evenly spread across the population. <a href="https://nei.nih.gov/health/color_blindness/facts_about">Approximately 8–9% of adults</a> have some kind of color insensitivity. Color insensitivity can make it difficult to distinguish hues (red/green color blindness is the most common form), and some rare conditions prevent the perception of hue altogether. Commonplace vision problems like short- and near-sigtedness and astigmatism (among others) also affect how well folks perceive color and contrast.</p>
        <p>Contrast is key. <a href="#0">Section 508</a> — and, by extension, <a href="#0">WCAG 2.0</a> — sets a legal standard for the contrast level necessary between text and its background. The <a href="https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html">baseline AA contrast standard</a> is <code>4.5:1</code> for most text and <code>3.1:1</code> for large text (19px+ bold or 24px+ normal text).</p>
        <p><strong>USWDS helps teams choose accessible colors with a color grade system.</strong> Let’s look at the <code>Black</code> color family, in grades 5-100 (grade 0 is <code>white</code>):</p>

        <div class="border-pixel padding-base border-radius-small margin-top-double">
          <p class="font-sans-f6 font-weight-700 margin-top-0 margin-bottom-half">Black</p>
          <div class="g-row font-mono-f2 font-weight-400">
            <div class="g-col">
              <div class="background-color-white height-double"></div>
              <div class="text-align-center">0</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-5 height-double"></div>
              <div class="text-align-center">5</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-10 height-double"></div>
              <div class="text-align-center">10</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-20 height-double"></div>
              <div class="text-align-center">20</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-30 height-double"></div>
              <div class="text-align-center">30</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-40 height-double"></div>
              <div class="text-align-center">40</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-50 height-double"></div>
              <div class="text-align-center">50</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-60 height-double"></div>
              <div class="text-align-center">60</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-70 height-double"></div>
              <div class="text-align-center">70</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-80 height-double"></div>
              <div class="text-align-center">80</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black-90 height-double"></div>
              <div class="text-align-center">90</div>
            </div><!-- swwatch -->
            <div class="g-col">
              <div class="background-color-black height-double"></div>
              <div class="text-align-center">100</div>
            </div><!-- swwatch -->
          </div>
        </div>
        <p class="font-sans-f5 font-weight-400 max-width-measure-small line-height-base margin-y-base padding-bottom-base"><strong>Above:</strong> Each color family has ten grades, from 5-90. Pure <strong>white</strong> is the equivalent of grade 0, and pure <strong>black</strong> is the equivalent of grade 100. Across families, grades have the same gray value — that is, when seen in grayscale any color of the same grade will look the same.</p>

        <p>The difference in grades between two colors is meaningful. Use this difference to quickly calculate contrast. Across all colors and color familes:</p>
        <ul>
          <li><strong>Grade differences (deltas) of 50</strong> between any two colors assure that the contrast between the two colors conforms to <span class="color-red-60v">WCAG 2.0 AA</span>. (Like between <code>black-90</code> and <code>red-40</code>.) </li>
          <li><strong>Grade differences (deltas) of 40</strong> between any two colors assure that the contrast between the two colors conforms to <span class="color-red-60v">WCAG 2.0 AA Large</span>. (Like between <code>black-90</code> and <code>indigo-warm-50v</code>.) </li>
        </ul>

          <div class="g-row g-gap font-mono-f2 font-weight-400">
            <div class="g-col">
              <div class="background-color-black-90 padding-base  padding-bottom-base-plus border-radius-small is-inverse">
                <div class="color-black-40 font-mono-f1 margin-bottom-double font-weight-400"><span class="font-sans-f2">background color:</span><span class="color-white-1"> Black 90</span></div>
                <div class="color-black-50 font-sans-f16 line-height-smallest margin-y-0 font-weight-700">Black 50</div>
                <div class="font-mono-f1 line-height-smallest font-weight-400 color-black-30 border-top-pixel border-color-black-70 padding-top-half margin-top-quarter g-row">
                  <div class="g-col"><span class="font-sans-f2">text color:</span><span class="color-white-1"> Black 50</span></div>
                  <div class="g-col-2"><span class="font-sans-f2">delta:</span><span class="color-white-1"> 40</span></div>
                  <div class="g-col-2"><span class="font-sans-f2">size:</span><span class="color-white-1"> 80px</span></div>
                  <div class="g-col-4 text-align-right"><span class="font-sans-f2">contrast:</span><span class="color-white-1"> 3.89:1 (AA Large)</span></div>
                </div>
                <div class="color-black-40 font-sans-f6 line-height-smallest padding-0 margin-top-double">Black 50: a grade difference of 50+ conforms to Section 508 AA.</div>
                <div class="font-mono-f1 line-height-smallest font-weight-400 color-black-30 border-top-pixel border-color-black-70 padding-top-half margin-top-half-plus g-row">
                  <div class="g-col"><span class="font-sans-f2">text color:</span><span class="color-white-1"> Black 40</span></div>
                  <div class="g-col-2"><span class="font-sans-f2">delta:</span><span class="color-white-1"> 50</span></div>
                  <div class="g-col-2"><span class="font-sans-f2">size:</span><span class="color-white-1"> 17px</span></div>
                  <div class="g-col-4 text-align-right"><span class="font-sans-f2">contrast:</span><span class="color-white-1"> 5.69:1 (AA)</span></div>
                </div>
              </div>
            </div>
          </div>

          <div class="g-row g-gap font-mono-f2 font-weight-400 margin-y-double">
            <div class="g-col">
              <div class="background-color-black-90 padding-base  padding-bottom-base-plus border-radius-small is-inverse">
                <div class="color-black-40 font-mono-f1 margin-bottom-double font-weight-400">background color: <span class="color-white-1">Black 90</span></div>
                <div class="color-indigo-warm-50v font-sans-f16 line-height-smallest margin-y-0 font-weight-700">Indigo warm 50v</div>
                <div class="font-mono-f1 line-height-smallest font-weight-400 color-black-30 border-top-pixel border-color-black-70 padding-top-half margin-top-quarter g-row">
                  <div class="g-col"><span class="font-sans-f2">text color:</span><span class="color-white-1"> Indigo warm 50v</span></div>
                  <div class="g-col-2"><span class="font-sans-f2">delta:</span><span class="color-white-1"> 40</span></div>
                  <div class="g-col-2"><span class="font-sans-f2">size:</span><span class="color-white-1"> 80px</span></div>
                  <div class="g-col-4 text-align-right"><span class="font-sans-f2">contrast:</span><span class="color-white-1"> 3.89:1 (AA Large)</span></div>
                </div>
                <div class="color-red-warm-40v font-sans-f6 line-height-smallest padding-0 margin-top-double">Red warm 40v: A grade difference of 40+ conforms to Section 508 AA Large.</div>
                <div class="font-mono-f1 line-height-smallest font-weight-400 color-black-30 border-top-pixel border-color-black-70 padding-top-half margin-top-half-plus g-row">
                  <div class="g-col"><span class="font-sans-f2">text color:</span><span class="color-white-1"> Red warm 40v</span></div>
                  <div class="g-col-2"><span class="font-sans-f2">delta:</span><span class="color-white-1"> 50</span></div>
                  <div class="g-col-2"><span class="font-sans-f2">size:</span><span class="color-white-1"> 17px</span></div>
                  <div class="g-col-4 text-align-right"><span class="font-sans-f2">contrast:</span><span class="color-white-1"> 5.36:1 (AA)</span></div>
                </div>
              </div>
            </div>
          </div>

          <figure class="margin-top-double margin-x-0 display-block">
            <div class="border-pixel border-radius-small padding-double">
              <img class="max-width-full display-block margin-x-auto" src="{{ '/assets/img/uswds/color-grades-chart.webp' | relative_url }}" alt="A chart showing how grade differences of 50 conform to WCAG AA and differences of 40 conform to WCAG AA Large">
            </div>
            <figcaption class="font-sans-f5 font-weight-400 max-width-measure-small line-height-base margin-top-base-plus margin-bottom-base padding-bottom-base"><strong>Above:</strong> This data visualization shows the ten standard grades of a USWDS color family, as well as grade 0 (white) and grade 100 (black). Lightness is the lightness level of gray in the HSL color model. The delta column shows the difference in gray level between grades. The bars on the right show minimum conformant color pairs. Grade 50 will be WCAG 2.0 AA conformant against both pure black and pure white.</figcaption>
          </figure>

        <p>There should be no need for additional manual checking, but this system is relatively new, and it’s worth double checking to assure system integrity. If you find any problems, please <a href="https://github.com/uswds/uswds">file an issue</a> in the USWDS Github repo.</p>

        <p><strong>Don’t use color exclusively to convey meaning.</strong> Even Section 508 conformant contrast doesn’t assure that colors are distinguishable for a significant percentage of your audience. <a href="https://nei.nih.gov/health/color_blindness/facts_about">Approximately 8–9% of the population</a> has some kind of color insensitivity, especially between red and green. Color should only be used as progressive enhancement — if a certain color is the only indicator of a message, that message won’t get through to many many people.</p>

        <h2 class="font-sans-f10 margin-top-double margin-bottom-double border-top-pixel padding-top-base">USWDS color wheels</h2>
        <p>The following color wheels are a way to visualize the entire USWDS system palette and its color family naming rubric. The color wheels are arranged around the 360° of the <a href="#0">HSL color model</a>. Each color family is labelled with its general position on this model. In general, colors within color families stay close to the hue value listed, but it is a custom palette, not generated by an algorithm. Some hue variation within color families is intentional — we are trying to find good colors, not just those that fit a function.</p>
        <p>The vivid palette is incomplete. We’ve added vivid variants as we’ve found a project need. This number will continue to grow and we <a href="#0">welcome new suggetions</a> in our Github repo for vivid variants where none currently exist.</p>

        <figure class="margin-top-double margin-x-0 margin-bottom-0 display-block padding-double background-color-white border-top-radius-large">
            <div class="text-align-center font-sans-f8 font-weight-300 margin-bottom-double">USWDS base color wheel</div>
            <img class="max-width-full display-block margin-x-auto" src="{{ '/assets/img/uswds/uswds-standard-color-wheel.webp' | relative_url }}" alt="A color wheel showing the standard USWDS color families arranged around the 360° of the HSL color model">
        </figure>
        <figure class="margin-top-double margin-x-0 margin-top-0 display-block padding-double padding-top-base background-color-white border-bottom-radius-large">
          <div class="text-align-center font-sans-f8 font-weight-300 margin-bottom-double border-top-pixel padding-top-triple">USWDS vivid color wheel</div>
          <img class="max-width-full display-block margin-x-auto" src="{{ '/assets/img/uswds/uswds-vivid-color-wheel.webp' | relative_url }}" alt="A color wheel showing the standard USWDS color families arranged around the 360° of the HSL color model">
        </figure>

        <h2 class="font-sans-f10 margin-top-double margin-bottom-double border-top-pixel padding-top-base">Using color</h2>

        <p>If we use color intentionally, consistently, and sensitively, it can make a big difference in the way people understand and connect with our pages, our products and services, and our message. Color is an important component of visual and emotional cognition, and that’s precisely what makes it difficult to use well — what’s strong and confident to one person can be jarring or alarming to another.</p>
        <p><strong>Start in black and white.</strong> Start with your core message and use <a>type scale</a> and <a>heierarchy</a> to test and refine its effectiveness. Then introduce color to support that message. Color can overwhelm interpretation, and since <a href="https://nei.nih.gov/health/color_blindness/facts_about">approximately 8–9% of the population</a> has some kind of color insensitivity, it’s important not to rely on color to convey information critical to your message.</p>
        <p><strong>Put the practical before the emotional.</strong> Because color can do so much, it can be smart to be focused. Limit the complexity of color by concentrating on </p>
        <p><strong>Use mood boards.</strong> If we use color intentionally, consistently, and sensitively, it can make a big difference in the way people understand and connect with our pages, our products, and our message. Color is an important component of visual and emotional cognition, but that’s precisely what makes it difficult to use well.</p>

        <h2 class="font-sans-f10 margin-top-double margin-bottom-double border-top-pixel padding-top-base">Pairing colors</h2>
        <p>Section TK</p>

        <h2 class="font-sans-f10 margin-top-double margin-bottom-double border-top-pixel padding-top-base">References</h2>
        <p>Section TK</p>



      </div>
    </div>

  </div><!-- l.container -->
</div><!-- div -->