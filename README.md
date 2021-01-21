# HW2
Homework 2

Deployed site: https://tender-kirch-80dbeb.netlify.app/index.html

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KIEI-451: Week 2 Homework</title>
  <link href="https://unpkg.com/tailwindcss@2/dist/tailwind.min.css" rel="stylesheet" type="text/css">
</head>

<body>
  <div class="container mx-auto py-8">
    <h1 class="text-lg uppercase text-gray-500 font-bold">KIEI-451: Introduction to Software Development</h1>
    <h2 class="text-2xl font-bold my-4">Week 2 Homework Instructions</h2>
    <div class="mt-4 space-y-4">
      <p>This week, you will expand the business website that you created in the first homework, adding styling using the Tailwind CSS framework. In addition, you'll add a form to add user interactivity to your website. The form can be for any purpose that makes sense in the context of what you're building – contact form, order form, survey, etc. Finally, you'll host your site on the Internet using Netlify and accept public form submissions.</p>
      <p>Begin by creating a new repository in your GitHub account. Name this repository <span class="bg-orange-100 text-red-400 font-mono p-1">hw2</span> and clone the repository to your computer. Don't try to rename your project from last week or otherwise copy-and-paste/duplicate the folder from last week in order to create your <span class="bg-orange-100 text-red-400 font-mono p-1">hw2</span> repository – start from scratch, copying individual HTML files and images if you need to.</p>
      <h3 class="font-bold text-xl">Style Guidelines</h3>
      <p>On your 3+ existing web pages, you should implement the Tailwind framework by adding class names to elements that will affect your website's:</p>
      <ol class="list-decimal list-inside">
        <li>Colors</li>
        <li>Typography</li>
        <li>Borders</li>
        <li>Sizing</li>
        <li>Box Model</li>
        <li>Layout (Flexbox)</li>
        <li>Responsive Design</li>
      </ol>
      <p>This is <strong>not</strong> a design class; your work will not be judged on how well your pages are actually designed. Just do your best to make it look like a real website you'd find in the wild, aside from the requirements as described in the rubric.</p>
      <h3 class="font-bold text-xl">Rubric (10 points total)</h3>

      <ul class="list-disc list-inside">
        <li>3 points: adding the Tailwind CSS framework to all of your website's pages, and add Tailwind CSS classes to the existing elements. At least one class should be added to the page to affect an element's color, typography, borders, sizing, and box model.</li>
        <li>3 points: At least one flexbox (left-to-right) layout element should be present. This element should appear stacked (i.e. not left-to-right but rather top-to-bottom) on a small device screen, like a phone in vertical orientation.</li>
        <li>2 points: Add a form to at least one of your web pages – it can be intended to capture any type of information, and be able to be successfully submitted to Netlify on your live site.</li>
        <li>2 points: Your site should be launched live on the Internet using Netlify. <strong>Important!</strong> In the <code>README.md</code> located in your project's root, include the full Internet URL (e.g. <code>https://yourapp.netlify.app/</code>) of your website. This is the only way we will know the publicly available location and for you to receive full credit for this requirement.</li>
      </ul>

      <p class="my-4">Finally, and once again, be sure to&nbsp;<span style="text-decoration: underline;"><strong>submit your Github repository's URL via
            Canvas</strong></span><strong> - this is the ONLY way we will know what your Github username is and where your finished code lives!</p>
    </div>
</body>

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KIEI-451: Week 2 Lab</title>
  <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet" type="text/css">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.22.0/themes/prism.min.css" rel="stylesheet" type="text/css">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.22.0/plugins/line-numbers/prism-line-numbers.min.css"
    rel="stylesheet" type="text/css">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.22.0/prism.min.js"></script>
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.22.0/plugins/line-numbers/prism-line-numbers.min.js"></script>
</head>
<body>
  <div class="container mx-auto py-8">
    <h1 class="text-lg uppercase text-gray-500 font-bold">KIEI-451: Introduction to Software Development</h1>
    <h2 class="text-2xl font-bold">Week 2 Lab Instructions</h2>
    
    <div class="mt-4 space-y-4">
      <h3 class="text-xl font-bold">Styling Musiccessories</h3>
      <ol class="list-decimal list-inside">
        <li>Create a brand-new repository on GitHub. Name the repo <span class="bg-orange-100 text-red-400 font-mono p-1">week2-lab</span> and clone/open it in VSCode.</li>
        <li>Create a new file named <span class="bg-orange-100 text-red-400 font-mono p-1">index.html</span>. Use <span class="bg-orange-100 text-red-400 font-mono p-1">lab/musiccessories-unstyled.html</span> as the starting point (i.e. copy-and-paste the source) for your newly-created <span class="bg-orange-100 text-red-400 font-mono p-1">index.html</span>.</li>
        <li>Add the Tailwind CSS framework to the unstyled page, and add Tailwind class names to the existing elements to make it look similar to the wireframe below.</li>
        <li>Add an order form to the bottom of the page (similar to the wireframe) and follow the instructions below to get your page publicly hosted on Netlify and accepting form submissions.</li>
        <li>Click the "Source Control" icon in the left-hand sidebar, commit and push your changes.</li>
      </ol>

      <h3 class="text-xl font-bold">Netlify – Hosting</h3>
      <p>This quarter, we'll be using a free service called <a href="https://netlify.com/" target="_blank" class="text-pink-500 underline">Netlify</a> to publicly host our websites and applications. If you haven't already, please set up an account to use – <strong>you'll want to log-in with your GitHub login when initially signing up.</strong> This will allow you to automatically link your GitHub repositories to your public Netlify apps.</p>
      <p>Creating a new Netlify app is straightforward; simply log-in to your Netlify account and select "New site from Git". Follow the prompts to connect to your GitHub account and select a repository to deploy. <strong>The GitHub repository we connect to must have a <span class="bg-orange-100 text-red-400 font-mono p-1">index.html</span> in the root of its directory structure.</strong></p>

      <h3 class="text-xl font-bold">Netlify – Forms</h3>
      <p>Netlify has built-in functionality to accept form data. When your site is hosted on Netlify, we simply need to add a <span class="bg-orange-100 text-red-400 font-mono p-1">netlify</span> attribute to our <span class="bg-orange-100 text-red-400 font-mono p-1">form</span> tags for this to work. Essentially, this attribute triggers a little bit of JavaScript on Netlify's end, in order to automatically add the form's <span class="bg-orange-100 text-red-400 font-mono p-1">action</span> when submitting the form. Note that this only works on the publicly available site that's hosted on Netlify – not the development version that lives on your computer. Here's a quick example:</p>

      <pre class="m-0 p-0">
        <code class="language-html">
&lt;form netlify&gt;
  &lt;label class=&quot;block mt-4 font-bold&quot; for=&quot;name&quot;&gt;What is your name?&lt;/label&gt;
  &lt;input class=&quot;p-2 w-64 border border-gray-400 rounded shadow-xl focus:outline-none focus:ring-purple-500
  focus:border-purple-500&quot; type=&quot;text&quot; id=&quot;name&quot; name=&quot;name&quot;&gt;

  &lt;label class=&quot;block mt-4 font-bold&quot; for=&quot;favorite-color&quot;&gt;What is your favorite
  color?&lt;/label&gt;
  &lt;input class=&quot;p-2 w-64 border border-gray-400 rounded shadow-xl focus:outline-none focus:ring-purple-500
  focus:border-purple-500&quot; type=&quot;text&quot; id=&quot;favorite-color&quot; name=&quot;favoriteColor&quot;&gt;

  &lt;button class=&quot;block mt-4 text-white bg-purple-500 rounded px-4 py-2&quot;&gt;Submit form!&lt;/button&gt;
&lt;/form&gt;</code>
      </pre>

      <h3 class="text-xl font-bold">Musiccessories Mockup</h3>
      <p><img class="w-full" src="musiccessories.png"></p>
    </div>

  </div>
</body>
</html>

</html>
