Text can be **bold**, *italic*, or ~~strikethrough~~. [Links](https://gohugo.io) should be blue with no underlines (unless hovered over).

There should be whitespace between paragraphs. Vape migas chillwave sriracha poutine try-hard distillery. Tattooed shabby chic small batch, pabst art party heirloom letterpress air plant pop-up. Sustainable chia skateboard art party banjo cardigan normcore affogato vexillologist quinoa meggings man bun master cleanse shoreditch readymade. Yuccie prism four dollar toast tbh cardigan iPhone, tumblr listicle live-edge VHS. Pug lyft normcore hot chicken biodiesel, actually keffiyeh thundercats photo booth pour-over twee fam food truck microdosing banh mi. Vice activated charcoal raclette unicorn live-edge post-ironic. Heirloom vexillologist coloring book, beard deep v letterpress echo park humblebrag tilde.

90’s four loko seitan photo booth gochujang freegan tumeric listicle fam ugh humblebrag. Bespoke leggings gastropub, biodiesel brunch pug fashion axe meh swag art party neutra deep v chia. Enamel pin fanny pack knausgaard tofu, artisan cronut hammock meditation occupy master cleanse chartreuse lumbersexual. Kombucha kogi viral truffaut synth distillery single-origin coffee ugh slow-carb marfa selfies. Pitchfork schlitz semiotics fanny pack, ugh artisan vegan vaporware hexagon. Polaroid fixie post-ironic venmo wolf ramps **kale chips**.

>There should be no margin above this first sentence.
>Blockquotes should be a lighter gray with a border along the left side in the secondary color.
>There should be no margin below this final sentence.


## First Header 2

This is a normal paragraph following a header. Knausgaard kale chips snackwave microdosing cronut copper mug swag synth bitters letterpress glossier **craft beer**. Mumblecore bushwick authentic gochujang vegan chambray meditation jean shorts irony. Viral farm-to-table kale chips, pork belly palo santo distillery activated charcoal aesthetic jianbing air plant woke lomo VHS organic. Tattooed locavore succulents heirloom, small batch sriracha echo park DIY af. Shaman you probably haven’t heard of them copper mug, crucifix green juice vape *single-origin coffee* brunch actually. Mustache etsy vexillologist raclette authentic fam. Tousled beard humblebrag asymmetrical. I love turkey, I love my job, I love my friends, I love Chardonnay!

Deae legum paulatimque terra, non vos mutata tacet: dic. Vocant docuique me plumas fila quin afuerunt copia haec o neque.

On big screens, paragraphs and headings should not take up the full container width, but we want tables, code blocks and similar to take the full width.

Scenester tumeric pickled, authentic crucifix post-ironic fam freegan VHS pork belly 8-bit yuccie PBR&B. **I love this life we live in**.

## Second header 2

>This is a blockquote following a header. Bacon ipsum dolor sit amet t-bone doner shank drumstick, pork belly porchetta chuck sausage brisket ham hock rump pig. Chuck kielbasa leberkas, pork bresaola ham hock filet mignon cow shoulder short ribs biltong.

### Header 3

```
This is a code block following a header.
```
Next level leggings before they sold out, PBR&B church-key shaman echo park. Kale chips occupy godard whatever pop-up freegan pork belly selfies. Gastropub Belinda subway tile woke post-ironic seitan. Shabby chic man bun semiotics vape, chia messenger bag plaid cardigan.

#### Header 4

-This is an unordered list following a header.
-This is an unordered list following a header.
-This is an unordered list following a header.

##### Header 5

1. This is an ordered list following a header.
1. This is an ordered list following a header.
1. This is an ordered list following a header.

| What | Follows |
|:--:|:--:|
|A table | A header |
|A table | A header |
|A table | A header |

---

There’s a horizontal rule above and below this.

---

Here is an unordered list:

- Liverpool F.C.
- Chelsea F.C.
- Manchester United F.C.

And an ordered list:

1. Michael Brecker
1. Seamus Blake
1. Branford Marsalis

And an unordered task list:

- [x] Create a Hugo theme
- [x] Add task lists to it
- [ ] Take a vacation

And a “mixed” task list:

- [x] Pack bags
- ?
- [x]  Travel!

And a nested list:

* Jackson 5

    - Michael
    - Tito
    - Jackie
    - Marlon
    - Jermaine
* TMNT
    - Leonardo
    - Michelangelo
    - Donatello
    - Raphael

Definition lists can be used with Markdown syntax. Definition headers are bold.

**Name**

Godzilla

**Born**

1952

**Birthplace**

Japan

**Color**

Green

---

Tables should have bold headings and alternating shaded rows.

| Artist | Album | Year |
|:--:|:--:|:--:|
Michael|Jackson	Thriller|1982|
Prince|Purple Rain|1984
Beastie Boys|License to Ill|1986

If a table is too wide, it should scroll horizontally.

---


---

Code snippets like ```var foo = "bar";``` can be shown inline.

Also, ```this should vertically align``` ~~```with this``` and this~~.

Code can also be shown in a block element.

```
foo := "bar";
bar := "foo";
```

Code can also use syntax highlighting.

``` javascript
func main() {
  input := `var foo = "bar";`

  lexer := lexers.Get("javascript")
  iterator, _ := lexer.Tokenise(nil, input)
  style := styles.Get("github")
  formatter := html.New(html.WithLineNumbers())

  var buff bytes.Buffer
  formatter.Format(&buff, style, iterator)

  fmt.Println(buff.String())
}
```

```Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.```