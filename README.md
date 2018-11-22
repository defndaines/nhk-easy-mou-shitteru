# NHK Easy もう知ってる

**Work in Progress** 

Browser extension to remove furigana from known kanji when viewing articles at
[NHK News Web Easy](https://www3.nhk.or.jp/news/easy/).

This extension works by scanning the `<h1>` and article body for kanji with
furigana indicated using `<ruby>` tags. It then checks to see if the kanji are
in the set of known kanji (currently hard-coded to my WaniKani level). If the
kanji are already known, it then removes the furigana, thus removing
unnecessary hints that instead check whether the reader actually knows the
kanji.
