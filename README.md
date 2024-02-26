- 👋 Hi, I’m @Dragonfly5596
- 👀 I’m interested in ...outdoorandindoormelodyjane. im from the 90210.
- 🌱 I’m currently learning ...coding and how to lead 
- 💞️ I’m looking to collaborate on ...ZPN
- 📫 How to reach me ... amandamangiliman2@gmail.com
- 😄 Pronouns: ...LoveoutLoud
- ⚡ Fun fact: ...thebibleisfabricated. fun i swear.
import puppeteer from 'puppeteer';

(async () => {
  // Launch the browser and open a new blank page
  const browser = await puppeteer.launch();
  const page = await browser.newPage();

  // Navigate the page to a URL
  await page.goto('https://developer.chrome.com/');

  // Set screen size
  await page.setViewport({width: 1080, height: 1024});

  // Type into search box
  await page.type('.devsite-search-field', 'automate beyond recorder');

  // Wait and click on first result
  const searchResultSelector = '.devsite-result-item-link';
  await page.waitForSelector(searchResultSelector);
  await page.click(searchResultSelector);

  // Locate the full title with a unique string
  const textSelector = await page.waitForSelector(
    'text/Customize and automate'
  );
  const fullTitle = await textSelector?.evaluate(el => el.textContent);

  // Print the full title
  console.log('The title of this blog post is "%s".', fullTitle);
npm i puppeteer
# or using yarn
yarn add puppeteer
# or using pnpm
pnpm i puppeteerconst {join} = require('path');

/**
 * @type {import("puppeteer").Configuration}
 */
module.exports = {
  // Changes the cache location for Puppeteer.
  cacheDirectory: join(__dirname, '.cache', 'puppeteer'),
};import puppeteer from 'puppeteer';
page.click
(async () => {
  // Launch the browser and open a new blank page
  const browser = await puppeteer.launch();
  const page = await browser.newPage();
page.click
  // Navigate the p
  await browser.close();
})();
<!---
Dragonfly5596/Dragonfly5596 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->mangilimandragonsfly@gmail.com
AmLi-Morrid 
