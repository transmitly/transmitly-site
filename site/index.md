---
layout: default
title: Transmit.ly
nav_order: 1
description: "Vendor-agnostic messaging pipelines for Email, SMS, Voice, and Push with templates and delivery reports."
permalink: /
body_class: tl-home
image: /assets/images/oss-icon-dark.png
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "SoftwareApplication",
  "name": "Transmitly",
  "applicationCategory": "Communication",
  "operatingSystem": "Cross-platform",
  "url": "https://transmit.ly",
  "license": "https://www.apache.org/licenses/LICENSE-2.0",
  "creator": {
    "@type": "Organization",
    "name": "Code Impressions / CiLabs"
  },
  "sameAs": [
    "https://github.com/codeimpressions/transmitly",
    "https://github.com/transmitly/transmitly"
  ]
}
</script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Is Transmitly vendor-agnostic?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. You can start with SMTP and switch to SendGrid, Twilio, Infobip, or Firebase without changing your application code."
      }
    },
    {
      "@type": "Question",
      "name": "Which channels does Transmitly support?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Email, SMS, Voice, and Push out of the box. You can also add custom channels and providers."
      }
    },
    {
      "@type": "Question",
      "name": "Can I use my own templates?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. Transmitly supports Fluid and Scriban template engines, and you can point to remote or embedded templates."
      }
    }
  ]
}
</script>

<div class="tl-hero">
  <div class="tl-hero__orb tl-hero__orb--left">xxxxx</div>
  <div class="tl-hero__orb tl-hero__orb--right"></div>
  <div class="tl-ribbon">Apache 2.0</div>
  <div class="tl-hero__grid">
    <div class="tl-hero__brand tl-hero__brand--stacked">
      <img src="/assets/images/oss-icon-dark.png" alt="Transmitly OSS logo">
      <h1>Transactional communciations that scale with your app.</h1>
    </div>
    <div class="tl-hero__grid-inner">
      <div class="tl-hero__copy">
      <p class="tl-lede">Design communications once, deliver across Email / SMS / Voice / Push with pipelines, templates, and delivery reports built in.</p>
      <div class="tl-cta">
        <a class="btn btn-primary tl-btn-icon" href="https://github.com/transmitly/transmitly">
          <span class="tl-icon tl-icon--github" aria-hidden="true"></span> View on GitHub
        </a>
        <a class="btn btn-secondary" href="#get-started">Get started</a>
      </div>
      <div class="tl-meta">
        <div class="tl-meta__item">
          <span>Channels</span>
          <strong>Email / SMS / Voice / Push</strong>
        </div>
        <div class="tl-meta__item">
          <span>Provider agnostic</span>
          <strong>Swap SMTP, SendGrid, Twilio, Infobip, Firebase</strong>
        </div>
        <div class="tl-meta__item">
          <span>Templates</span>
          <strong>Fluid or Scriban, defined once per intent</strong>
        </div>
      </div>
    </div>
      <div class="tl-hero__panel">
        <p class="tl-panel__eyebrow">Delivery playbook</p>
        <h3 class="tl-panel__title">Pipeline &rarr; Provider &rarr; Delivery</h3>
        <div class="tl-panel__card">
          <div class="tl-panel__row">
            <span class="tl-dot tl-dot--primary"></span>
            <div>
              <p class="tl-panel__label">Define the pipeline</p>
              <p class="tl-panel__copy">Compose channel + template once per intent.</p>
            </div>
          </div>
          <div class="tl-panel__row">
            <span class="tl-dot tl-dot--accent"></span>
            <div>
              <p class="tl-panel__label">Pick the provider</p>
              <p class="tl-panel__copy">Start with SMTP; swap SendGrid, Twilio, Infobip, Firebase in a central location.</p>
            </div>
          </div>
          <div class="tl-panel__row">
            <span class="tl-dot tl-dot--muted"></span>
            <div>
              <p class="tl-panel__label">Dispatch & observe</p>
              <p class="tl-panel__copy">Send from your app and collect delivery reports with ease.</p>
            </div>
          </div>
        </div>
        <div class="tl-panel__foot">Vendor-agnostic, template-friendly, and ready for your stack.</div>
      </div>
    </div>
  </div>
</div>

<div class="tl-section">
  <h2>Why teams pick Transmitly</h2>
  <div class="tl-grid tl-grid--three">
    <div class="tl-card">
      <p class="tl-card__eyebrow">Strategy first</p>
      <h3>Pipeline-driven delivery</h3>
      <p>Centralize how each communication is composed and dispatched across channels.</p>
    </div>
    <div class="tl-card">
      <p class="tl-card__eyebrow">Adapter friendly</p>
      <h3>No provider lock-in</h3>
      <p>Switch from SMTP to SendGrid, Twilio or Infobip without touching your business logic.</p>
    </div>
    <div class="tl-card">
      <p class="tl-card__eyebrow">Visibility</p>
      <h3>Track every delivery</h3>
      <p>Capture delivery reports from providers and route them into your logs, alerts, or dashboards.</p>
    </div>
  </div>
</div>

<div class="tl-section" id="get-started">
  <div class="tl-grid tl-grid--two tl-grid--split">
    <div>
      <h2>Get started in minutes</h2>
      <ol class="tl-steps">
        <li><strong>Install</strong><br>Bring in Transmitly (and the SMTP provider to start).</li>
        <li><strong>Wire a provider</strong><br>Add your host, credentials, and defaults.</li>
        <li><strong>Declare a pipeline</strong><br>Define channels and templates for your intent.</li>
        <li><strong>Dispatch</strong><br>Send and observe with delivery reports.</li>
      </ol>
      <div class="tl-inline-cards">
        <div class="tl-inline-card">
          <p class="tl-card__eyebrow">dotnet CLI</p>
          <code>dotnet add package Transmitly<br>dotnet add package Transmitly.ChannelProvider.Smtp</code>
        </div>
      </div>
    </div>
    <div class="tl-card tl-card--code">
      <h3 class="tl-card__eyebrow">Configure &amp; dispatch</h3>
{% highlight csharp %}
using Transmitly;

ICommunicationsClient communicationsClient = new CommunicationsClientBuilder()
    .AddSmtpSupport(options =>
    {
        options.Host = "smtp.example.com";
        options.Port = 587;
        options.UserName = "MySMTPUsername";
        options.Password = "MyPassword";
    })
    .AddPipeline("WelcomeKit", pipeline =>
    {
        pipeline.AddEmail("welcome@my.app".AsIdentityAddress("Welcome Committee"), email =>
        {
            email.Subject.AddStringTemplate("Thanks for creating an account!");
            email.HtmlBody.AddStringTemplate("Check out the <a href=\"https://my.app/getting-started\">Getting Started</a> section to see all the cool things you can do!");
            email.TextBody.AddStringTemplate("Check out the Getting Started (https://my.app/getting-started) section to see all the cool things you can do!");
        });
    })
    .BuildClient();

builder.Services.AddSingleton(communicationsClient);

// Later in your app: dispatch by pipeline name and recipient address
var result = await communicationsClient.DispatchAsync("WelcomeKit", "newuser@example.com", new { });
{% endhighlight %}
      <p class="tl-card__foot">Swap providers or adjust templates in one place—your app code stays clean. <a href="https://github.com/transmitly/transmitly#changing-channel-providers">Learn how to change providers</a>.</p>
    </div>
  </div>
</div>

<div class="tl-section" id="samples">
  <h2>Samples to the ideas flowing</h2>
  <div class="tl-grid tl-grid--three">
    <div class="tl-card">
      <h3>Kitchen Sink (ASP.NET Core API)</h3>
      <p>All channels (Email/SMS/Voice/Push) with SMTP, SendGrid, Twilio, Infobip, Firebase, delivery reports, channel-provider restrictions, and Fluid templates.</p>
      <a class="tl-card__link" href="https://github.com/transmitly/transmitly/tree/main/samples/Transmitly.KitchenSink.AspNetCoreWebApi">View sample</a>
    </div>
    <div class="tl-card">
      <h3>Microservices</h3>
      <p>Extend the communications client with remote/embedded templates, persona filters, multi-tenant “from” resolution, and delivery reports across services.</p>
      <a class="tl-card__link" href="https://github.com/transmitly/transmitly/tree/main/samples/Microservices">View sample</a>
    </div>
    <div class="tl-card">
      <h3>Logger provider</h3>
      <p>A minimal provider that logs all channels—great for local testing and debugging dispatch behavior.</p>
      <a class="tl-card__link" href="https://github.com/transmitly/transmitly/tree/main/samples/Transmitly.ChannelProvider.Logger">View sample</a>
    </div>
  </div>
</div>

<div class="tl-section">
  <h2>Product checklist</h2>
  <div class="tl-grid tl-grid--three">
    <div class="tl-card">
      <h3>Operational confidence</h3>
      <p>Ship with pipelines, delivery reports, and templates defined in one place.</p>
    </div>
    <div class="tl-card">
      <h3>Friendly for builders</h3>
      <p>Readable APIs, clear defaults, and examples to unblock your team fast.</p>
    </div>
    <div class="tl-card">
      <h3>Community powered</h3>
      <p>Open source roadmap, issues, and discussions in GitHub to shape what ships next.</p>
    </div>
  </div>
</div>

<div class="tl-section tl-section--cta">
  <div class="tl-cta__card">
    <div>
      <div class="tl-pill-group">
        <p class="tl-pill tl-pill--ghost">Open Source</p>
        <p class="tl-pill tl-pill--ghost">Start dispatching today</p>
      </div>
      <h2>Drop Transmitly into your stack and keep building your app.</h2>
      <p class="tl-lede">&nbsp;</p>
    </div>
    <div class="tl-cta__actions">
      <a class="btn btn-primary tl-btn-icon" href="https://github.com/transmitly/transmitly">
        <span class="tl-icon tl-icon--github" aria-hidden="true"></span> Open GitHub
      </a>
      <a class="btn btn-secondary" href="https://github.com/transmitly/transmitly#quick-start">Follow the quickstart</a>
      <img class="tl-oss-logo" src="/assets/images/oss-icon-dark.png" alt="Transmitly OSS">
    </div>
  </div>
</div>

