# formsend-html-form
Send forms submission to your email using only HTML, no backend, no javascript.

##Quick Start

```html
<form action="https://formsend.ct.ws/php/submit.php?apikey=your-public-key" method="POST">
  <input type="email" name="email" required>
  <input type="text" name="message" required>
  <button type="submit">Send</button>
</form>

```
You can style the form as you see fit.
Live demo link: https://formsend.ct.ws/demo.html

##Why Formsend?
→ No backend required
→ Works with plain HTML
→ No javascript
→ Fast setup (under a min)
→ Free to start

##Use cases
→ Portfolio
→ Landing pages
→ Static sites (HTML, React, Next.js)
→ MVPs and quick builds

##React 
```html
export default function Contact()\
{
  return (
      <form action="https://formsend.ct.ws/php/submit.php?apikey=your-public-key" method="POST">
        <input type="email" name="email" required>
        <input type="text" name="message" required>
        <button type="submit">Send</button>
      </form>
  )
}
```
##Contributing

Feel free to add more examples.

#License
MIT
