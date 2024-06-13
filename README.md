# Stuff
-- idk really, but this can **probably help**

## - Discoveries -

First Discovery: **MathJax**: <br/>
  We figured out KH uses MathJax, a thing that renders high quality math stuff in JS and CSS. By @PlacidityIsEpic

Second Discovery: **kh-count-to**: <br/>
  A thing in the mathalon counter. Not much. By @PlacidityIsEpic

Third Discovery: **appjs.knowledgehook.com**: <br/>
  KH has its own website for JS scripts. It redirects you back to the normal KH tho. By @dates4u (formerly hi1cooler)

4th Discovery: **window**: <br/>
  Not much. By @dates4u (formerly hi1cooler)

5th Discovery: **getMathalonStars**: <br/>
  Checking the sources in the /app/ directory, you will see a file named **"common.ff7eefd85c2771ce.js"**.
  There is a function in it called getMathalonStars. It seemed like a big discovery.

  Inside the function there's this:
  ```js
  class o {
    // Other functions that won't be shown (there are if you check the sources)
  
    getMathalonStars(s) {
      const e = this.urlService.buildServerApiUrl("Teacher/MathalonRequirements", s);
      return this.httpClient.get(e)
    }
  }
  ```
