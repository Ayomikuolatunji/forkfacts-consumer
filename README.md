# ForkFacts Embedded Component

This is a proof-of-concept for embedding a component created in ff-producer into a third-party site using an embed code.

## Getting Started

To use the embedded component from forkfacts, follow these steps:

- Clone the ff-producer repository and deploy it to Vercel using their free account.
- Once deployed, copy the embed code provided on the website.
- Clone the ff-consumer repository and deploy it to Vercel using their free account.\*
- Paste the embed code copied in step 2 into the index.js file of the ff-consumer project.
- Deploy the ff-consumer project to Vercel.

## Usage

To use the embedded component in a third-party site, follow these steps:

- Copy the embed code provided on the ff-producer website.
- Paste the embed code into your HTML code where you want the component to be displayed.

## Copy code

```
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <h1>Welcome to my website</h1>
    <!-- Paste the embed code here -->
    <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
      <iframe src="https://forkfacts-v2.vercel.app/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"></iframe>
    </div>
 </body>
</html>

```

## Embed Code

The embed code is provided on the ff-producer website after the component is deployed. It should look something like this:

## Copy code

```
<!-- Copy and paste this code into your website where you want the component to be displayed -->
<div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe src="https://forkfacts-v2.vercel.app/" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"></iframe>
</div>
```

## Support

For any questions or issues, please contact the forkfacts support team.
