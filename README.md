# cheatsheet
A collection of tips and tricks for developpers.
To anybody who reads this, you are encouraged to propose new things via a pull request.

## Git
For a satisfying list of Github-flavored Mardown commands, visit [this link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

To discover Github's lingo, visit their [official glossary](https://docs.github.com/en/github/getting-started-with-github/github-glossary) webpage.

### Nested lists in Markdown

Lists look good. Get yourself out of the hell of organizing your list in Github's MD by following exactly how they do [there](https://github.com/defunkt/markdown-mode/blob/master/tests/nested-list.text).

### Pull a specific branch
When cloning or pulling a code, you may want to get a specific version of it. This is generally called a branch. This is how you do it (inspired from [this thread](https://precice.discourse.group/t/installation-of-precice-v2-and-its-openfoam-adapter/171/7)):

``` 
git clone --single-branch --branch OpenFOAM6 https://github.com/precice/openfoam-adapter.git
```

### Test a pull request before merging
(inspired from this [article](https://medium.com/@bolajiayodeji/how-to-test-a-pull-request-locally-before-merging-634bb205d3a6)).
   1. Get the ID of the branch you want to test. For instance the ID of `https://github.com/precice/openfoam-adapter/pull/121` is 121.
   2. Fetch it on your machine with the command `git fetch origin pull/ID/head`
   3. Make it the "considered" branch by checkin it out via the command `git checkout FETCH_HEAD` (Notice that it has been named FETCH_HEAD in step 2)

## Safe surf
This is a list of advices for enjoying a safe surfing of the web. It consists in a personal account of short and salient recomendations possibly accompagnied by an irrelevant comment.

   - Think twice before you click, just twice.
   
     French people overcomplicate it by "twisting their tongue seven times in their mouth before speaking", but really, as you should carve every word before you let it fall, you should only have the gumption whether to click or not after pointing. 

   - Review yourself.
   
     Proofread, check the meaning of your words and your tone, give your text a proper structure. Misunderstanding could lead to offense or a useless loss of time. This is true for literally everybody in every languages, and in particular for foreigners. When learning a new language or translating something, you may need to lean on resources more reliable than Google Translate (please do). Please consider resorting to some of the followings:
       1. [the thesaurus](https://www.thesaurus.com/) for synonyms and antonyms,
       2. [linguee](https://www.linguee.com/) for adapting idioms,
       3. [reverso dictionnary](https://dictionary.reverso.net/) for the same things. 
   - Be gentle.
    
     Being nice has nothing ideological, political or religious. Think of Saint Thomas' adage: "Believe what you see". Note: Not only "you can't see it, you don't believe in it", but you also are encouraged to embrace it if you witness it. It is basically the duck test from another perspective. Although in this context, I wanted to emphasize the importance of doing to people what you want them to do to you.

   - Browse smart.
   
     Coming: Google dorks, private browsing and keyboard shortcuts.
