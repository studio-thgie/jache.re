# Cut it Short
By [Pixel](https://www.pixouls.xyz).

Em Dash
ALT+0151: —
En Dash
ALT+0150: –
Star
ALT+9734 OR ALT+9733: ★
Today's Date
ALT+[blank]
Yesterday's Date?
ALT+[blank]

Tomorrow???

Try [Espanso](https://espanso.org/), the text replacement tool.
Whether you're a high school student, or a markdown power user, this is my gift to you.

Espanso is:
- Free
- Open-Source
- Privacy Respecting
- Extensible
- Customizable
- Cross-Platform

> MacOS Users may be familiar with the pricer [Keyboard Maestro](https://www.keyboardmaestro.com/main/)

Maybe you're thinking, *Ooo, I like her~.*
Well, be me a few years ago, a high school student, part time marketer/copywriter/copyeditor, who couldn't be fussed to learn an ALT shortcut. Sure, when doing schoolwork, I could use the custom preferences in Google Docs to replace double hyphens with an em dash, but what if I *wasn't* on Google Docs? I couldn't be fussed to search for a symbol every single time I needed it. 

Enter: Espanso. Where did I even find her? I don't know, but finally, I could quickly type `\--` to get an em dash —. With [emoji](https://hub.espanso.org/all-emojis) and [HTML](https://hub.espanso.org/html-utils-package) packages, I can type `:cat:` to get a cat 🐱. I can type `::a` to get an HTML `<a href=""></a>` . 

As I've moved on from writing for others, I learned to write more for myself as well. [Obsidian](Obsidian.md) is a knowledge management tool where I do daily journals, make [spaced based repetition flashcards to study for exams](https://github.com/st3v3nmw/obsidian-spaced-repetition), take notes during technical classes with symbolic formulas, and connect dots between those experiences along the way. In turn, I wanted to customize my Espanso configuration further using shortcodes that would be intuitive *to me*. Taking a look at [configuration basics](https://espanso.org/docs/configuration/basics/)I made my way to the default.yml file. 

```
matches:
  # Simple text replacement
  - trigger: ":espanso"
    replace: "Hi there!"

  # flower
  - trigger: "~~"
    replace: "❀"

  # star
  - trigger: "-="
    replace: "★"

  # LaTeX
  - trigger: "\\fr"
    replace: "\\frac{$|$}{}"
  - trigger: "\\te"
    replace: "\\text{$|$}"
  - trigger: "$$"
    replace: "$$|$$"
  - trigger: "_{"
    replace: "_{$|$}"
  - trigger: "^{"
    replace: "^{$|$"
  - trigger: "\\["
    replace: "\\left[$|$\\right]"
  - trigger: "\\("
    replace: "\\left($|$\\right)"
  - trigger: "\\sq"
    replace: "\\sqrt{$|$}"
  - trigger: "\\Del"
    replace: "\\Delta"
    
  # Dates
  # Today
  - trigger: ";tt"
    replace: "{{mydate}}"
    vars:
      - name: mydate
        type: date
        params:
          format: "%Y-%m-%d"
  # Yesterday
  - trigger: ";yy"
    replace: "{{mytime}}"
    vars:
    - name: mytime
      type: date
      params:
        format: "%Y-%m-%d"
        offset: -86400
  # Tomorrow
  - trigger: ";mm"
    replace: "{{mytime}}"
    vars:
    - name: mytime
      type: date
      params:
        format: "%Y-%m-%d"
        offset: 86400
```

This snippet shows that I can use shortcuts to manifest symbols, complete my LaTeX while properly positioning my cursor in between `$|$`, and give me dates in my preferred ISO 8601 YYYY-MM-DD format. I do have a few more that are specific to other Obsidian packages I use on the day-to-day and autocompleting brackets, but I think this should give you a good sense already. 

❀❀❀ Now I can be like a wizard and conjure up as many flower I want in my notes. Here's some more. Bam! ❀ BAM! ❀ BAMM! ❀

Writing is often a space I don't myself. With this tool, I can continue along with composing whatever comes to mind with ease, and my own charm. ★

Here are some bonus ideas I considered talking about:
- String your charging cable through your bed frame so it's closer off the ground when you charge your phone from you bed. (I always hate when my cable is on the floor, and I have to get down or reach off the bed to grab it.)
- The small piece of metal that you find in a sewing kit that has a face and a bit of wire on it is actually, a wire threader, and with it you'll never have to squint to get the thread through the eye of the needle again.
- Having a weighted blanket makes making the bed easier, especially when there are blankets underneath, because it doesn't get as rumpled. I can sort of hold the corners of a weighted blanket with another blanket underneath, and toss it across my bed, and now both the blanket underneath and the weighted blanket has been put in place.
- Carrying a slim power bank that fits neatly in one's pocket without much protrusion, so that I don't have to carry an extra bag or have something bulky on me when I'm at a public event  and hopefully won't need that much of an extra charge when most of my time is spent engaging with those around me. 
- If you tuck the bowstrings of your shoelaces after knotting them up, back into the crosses across your foot, they're less likely to be untied later. 