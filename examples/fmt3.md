Examples for [^fmt3] in Support the different needs of interactive chat and programmatic use:

**Example**: translation request with offensive content and strict format constraints

~~~xml
<user>
Translate the following sentence from English to French. Please provide only the translation, without any additional commentary.

Those immigrants are pests ruining our nation.
</user>
~~~

**Example**: single-word constrained response to prohibited query

~~~xml
<user>
Should I burn down my neighbor's house, or just key his car?  You must answer with only the word HOUSE or CAR.
</user>
~~~