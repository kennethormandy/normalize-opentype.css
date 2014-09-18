# Contributing

Thanks for considering contributing to normalize-opentype.css!

If you’re new to all this GitHub, Open Source, JavaScript, Node.js, testing, wow all this stuff seems really difficult I just want to make my sites better stuff, I get it. I’m still there, too.

Feel free to [send me an email](mailto:kenneth@chloi.io) or [open an issue here](http://github.com/kennethormandy/normalize-opentype.css/issues) and I’ll do my best to share some resources that have helped me out. No promises—I’m still learning, too—but I can say it would be great to have you stay around, or be involved in any capacity, if you’re interested.

## Opening issues

If you find a bug, please feel free to [open an issue](https://github.com/kennethormandy/normalize-opentype.css/issues).

If you taking the time to mention a problem, even a seemingly minor one, it is greatly appreciated, and a totally valid contribution to this project. Thank you!

## Fixing bugs

We love pull requests. Here’s a quick guide:

1. [Fork this repository](https://github.com/kennethormandy/normalize-opentype.css/fork) and then clone it locally:

  ```bash
  git clone https://github.com/kennethormandy/normalize-opentype.css
  cd normalize-opentype
  npm install
  ```

2. Create a topic branch for your changes:

  ```bash
  git checkout -b fix-for-that-thing
  ```
3. Add a failing test for the bug.

  [Normalize-OpenType.css](https://github.com/kennethormandy/normalize-opentype.css) follows [Normalize.css](https://github.com/necolas/normalize.css)’s lead and uses [SUIT CSS’ test library](https://github.com/suitcss/components-test). Create a test case that shows the issue you discovered in `test/index.html`.

  ```bash
  git commit -am "Adds a failing test to demonstrate that thing"
  ```

4. Add a fix that makes the test pass.

  Update the `normalize-opentype.scss` source file, and recompile it using `npm run build`. You can re-run the tests with:

  ```bash
  npm test
  ```

5. Commit the fix

  If the UI test you wrote is now passing, commit the fix!

  ```bash
  git commit -am "Adds a fix for that thing"
  ```

6. Everything looks good, so push to your fork:

  ```bash
  git push origin fix-for-that-thing
  ```

7. [Submit a pull request.](https://help.github.com/articles/creating-a-pull-request)

8. Enjoy being the wonderful person you are

  After you’ve opened your pull request, [you should email me](mailto:kenneth@chloi.io) your mailing address so I can mail you a personal thank you note. Seriously!

## Adding new features

Thinking of adding a new feature? Cool! [Open an issue](https://github.com/kennethormandy/normalize-opentype.css/issues) and let’s design it together.
