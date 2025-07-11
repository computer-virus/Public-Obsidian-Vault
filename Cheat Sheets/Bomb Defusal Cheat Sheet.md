# Bomb Defusal Cheat Sheet

## Information Gathering

> [!failure] Strikes: <input type="checkbox" style="margin-left: 8px; border-color: #FB464C;" /> <input type="checkbox" style="margin-left: 8px; margin-right: 16px; border-color: #FB464C;" /> Max: <input type="number" step="1" min="0" max="3" value="0" style="width: 32px; text-align: center; margin-left: 8px; color: #FB464C; background: none; border-color: #FB464C;" />

> [!list] Serial Number
> <label for="serial-vowel">Contains <b>Vowel</b> <input type="checkbox" id="serial-vowel" style="margin-left: 16px; border-color: #53DFDD;" /></label>
> 
> <label for="last-digit">Last Digit <b>Even</b> <input type="checkbox" id="last-digit" style="margin-left: 16px; border-color: #53DFDD;" /></label>

> [!warning] Batteries <input type="number" step="1" min="0" value="0" style="width: 32px; text-align: center; margin-left: 16px; color: #E9973F; background: none; border-color: #E9973F;" />

> [!list] Lit Indicators
> <label for="lit-car"><b>CAR</b> <input type="checkbox" style="margin-left: 16px; border-color: #53DFDD;" id="lit-car" /></label>
> 
> <label for="lit-frk"><b>FRK</b> <input type="checkbox" id="lit-frk" style="margin-left: 16px; border-color: #53DFDD;" /></label>
> 
> `*Note: Only indicators that have their light lit count.`


> [!note] <label for="par-port">Parallel Port <input type="checkbox" id="par-port" style="margin-left: 16px; border-color: #027AFF;" /></label>
> ![[Vault assets/Games/KTANE/Parallel Port.svg|256]]

## Modules

### Wires

<div style="display: flex; flex-direction: column; width: 155px; gap: 8px;">
	<input type="text" style="text-align: center; text-transform: uppercase;" placeholder="1st Wire" />
	<input type="text" style="text-align: center; text-transform: uppercase;" placeholder="2nd Wire" />
	<input type="text" style="text-align: center; text-transform: uppercase;" placeholder="3rd Wire" />
	<input type="text" style="text-align: center; text-transform: uppercase;" placeholder="4th Wire" />
	<input type="text" style="text-align: center; text-transform: uppercase;" placeholder="5th Wire" />
	<input type="text" style="text-align: center; text-transform: uppercase;" placeholder="6th Wire" />
</div>

> [!list]- 3 Wires
> - **No Red:** Cut 2nd
> - **Last White:** Cut Last
> - **>1 Blue:** Cut Last Blue
> - Cut Last

> [!list]- 4 Wires
> - **>1 Red & ODD:** Cut Last Red
> - **Last Yellow & No Red:** Cut 1st
> - **1 Blue:** Cut 1st
> - **>1 Yellow:** Cut Last
> - Cut 2nd

> [!list]- 5 Wires
> - **Last Black & ODD:** Cut 4th
> - **1 Red & >1 Yellow:** Cut 1st
> - **No Black:** Cut 2nd
> - Cut 1st

> [!list]- 6 Wires
> - **No Yellow & ODD:** Cut 3rd
> - **1 Yellow & > 1 White:** Cut 4th
> - **No Red:** Cut Last
> - Cut 4th

### The Button

<input type="text" style="text-align: center; text-transform: uppercase;" placeholder="Color" />
<input type="text" style="text-align: center; text-transform: uppercase;" placeholder="Label" />

![[Vault Assets/Games/KTANE/The Button.png]]

### Keypads

**Note: The white symbols are unique.**

|<center>Column 1</center>|<center>Column 2</center>|<center>Column 3</center>|<center>Column 4</center>|<center>Column 5</center>|<center>Column 6</center>|
|---|---|---|---|---|---|
|![[Vault Assets/Games/KTANE/Keypads/balloon.webp]]<div><label for="k-balloon1"><input type="checkbox" id="k-balloon1"/> **balloon**</label></div>|![[Vault Assets/Games/KTANE/Keypads/euro.webp]]<div><label for="k-euro1"><input type="checkbox" id="k-euro1" /> **euro**</label></div>|![[Vault Assets/Games/KTANE/Keypads/copyright.webp]]<div><label for="k-copy"><input type="checkbox" id="k-copy" /> **copyright**</label></div>|![[Vault Assets/Games/KTANE/Keypads/six.webp]]<div><label for="k-six1"><input type="checkbox" id="k-six1" /> **six**</label></div>|![[Vault Assets/Games/KTANE/Keypads/pitchfork.webp]]<div><label for="k-pitch1"><input type="checkbox" id="k-pitch1" /> **pitchfork**</label></div>|![[Vault Assets/Games/KTANE/Keypads/six.webp]]<div><label for="k-six2"><input type="checkbox" id="k-six2" /> **six**</label></div>|
|![[Vault Assets/Games/KTANE/Keypads/at.webp]]<div><label for="k-at"><input type="checkbox" id="k-at" /> **at**</label></div>|![[Vault Assets/Games/KTANE/Keypads/balloon.webp]]<div><label for="k-balloon2"><input type="checkbox" id="k-balloon2" /> **balloon**</label></div>|![[Vault Assets/Games/KTANE/Keypads/pumpkin.webp]]<div><label for="k-pump"><input type="checkbox" id="k-pump"/> **pumpkin**</label></div>|![[Vault Assets/Games/KTANE/Keypads/paragraph.webp]]<div><label for="k-para1"><input type="checkbox" id="k-para1" /> **paragraph**</label></div>|![[Vault Assets/Games/KTANE/Keypads/smileyface.webp]]<div><label for="k-smiley"><input type="checkbox" id="k-smiley" /> **smiley face**</label></div>|![[Vault Assets/Games/KTANE/Keypads/euro.webp]]<div><label for="k-euro2"><input type="checkbox" id="k-euro2" /> **euro**<label></div>|
|![[Vault Assets/Games/KTANE/Keypads/upsidedowny.webp]]<div><label for="k-y1"><input type="checkbox" id="k-y1" /> **upsidedown y**</label></div>|![[Vault Assets/Games/KTANE/Keypads/leftc.webp]]<div><label for="k-c1"><input type="checkbox" id="k-c1" /> **left c**</label></div>|![[Vault Assets/Games/KTANE/Keypads/cursive.webp]]<div><label for="k-cursive1"><input type="checkbox" id="k-cursive1" /> **cursive**</label></div>|![[Vault Assets/Games/KTANE/Keypads/bt.webp]]<div><label for="k-bt1"><input type="checkbox" id="k-bt1" /> **bt**</label></div>|![[Vault Assets/Games/KTANE/Keypads/bt.webp]]<div><label for="k-bt2"><input type="checkbox" id="k-bt2" /> **bt**</label></div>|![[Vault Assets/Games/KTANE/Keypads/tracks.webp]]<div><label for="k-tracks"><input type="checkbox" id="k-tracks" /> **tracks**</label></div>|
|![[Vault Assets/Games/KTANE/Keypads/squigglyn.webp]]<div><label for="k-n"><input type="checkbox" id="k-n" /> **squiggly n**</label></div>|![[Vault Assets/Games/KTANE/Keypads/cursive.webp]]<div><label for="k-cursive2"><input type="checkbox" id="k-cursive2" /> **cursive**</label></div>|![[Vault Assets/Games/KTANE/Keypads/doublek.webp]]<div><label for="k-doub1"><input type="checkbox" id="k-doub1" /> **doublek**</label></div>|![[Vault Assets/Games/KTANE/Keypads/squidknife.webp]]<div><label for="squid1"><input type="checkbox" id="squid1" /> **squid knife**</label></div>|![[Vault Assets/Games/KTANE/Keypads/rightc.webp]]<div><label for="k-rc"><input type="checkbox" id="k-rc" /> **right c**</label></div>|![[Vault Assets/Games/KTANE/Keypads/ae.webp]]<div><label for="k-ae"><input type="checkbox" id="k-ae" /> **ae**</label></div>|
|![[Vault Assets/Games/KTANE/Keypads/squidknife.webp]]<div><label for="k-squid2"><input type="checkbox" id="k-squid2" /> **squid knife**</label></div>|![[Vault Assets/Games/KTANE/Keypads/hollowstar.webp]]<div><label for="k-hollow1"><input type="checkbox" id="k-hollow1" /> **hollow star**</label></div>|![[Vault Assets/Games/KTANE/Keypads/meltedthree.webp]]<div><label for="k-three"><input type="checkbox" id="k-three" /> **melted three**</label></div>|![[Vault Assets/Games/KTANE/Keypads/doublek.webp]]<div><label for="k-doub2"><input type="checkbox" id="k-doub2" /> **doublek**</label></div>|![[Vault Assets/Games/KTANE/Keypads/paragraph.webp]]<div><label for="k-para2"><input type="checkbox" id="k-para2" /> **paragraph**</label></div>|![[Vault Assets/Games/KTANE/Keypads/pitchfork.webp]]<div><label for="k-pitch2"><input type="checkbox" id="k-pitch2" /> **pitchfork**</label></div>|
|![[Vault Assets/Games/KTANE/Keypads/hookn.webp]]<div><label for="k-hook1"><input type="checkbox" id="k-hook1" /> **hook n**</label></div>|![[Vault Assets/Games/KTANE/Keypads/hookn.webp]]<div><label for="k-hook2"><input type="checkbox" id="k-hook2" /> **hook n**</label></div>|![[Vault Assets/Games/KTANE/Keypads/upsidedowny.webp]]<div><label for="k-y2"><input type="checkbox" id="k-y2" /> **upsidedown y**</label></div>|![[Vault Assets/Games/KTANE/Keypads/questionmark.webp]]<div><label for="k-question1"><input type="checkbox" id="k-question1" /> **question mark**</label></div>|![[Vault Assets/Games/KTANE/Keypads/dragon.webp]]<div><label for="k-dragon"><input type="checkbox" id="k-dragon" /> **dragon**</label></div>|![[Vault Assets/Games/KTANE/Keypads/nwithhat.webp]]<div><label for="k-n-hat"><input type="checkbox" id="k-n-hat" /> **n with hat**</label></div>|
|![[Vault Assets/Games/KTANE/Keypads/leftc.webp]]<div><label for="k-c2"><input type="checkbox" id="k-c2" /> **left c**</label></div>|![[Vault Assets/Games/KTANE/Keypads/questionmark.webp]]<div><label for="k-question2"><input type="checkbox" id="k-question2" /> **question mark**</label></div>|![[Vault Assets/Games/KTANE/Keypads/hollowstar.webp]]<div><label for="k-hollow2"><input type="checkbox" id="k-hollow2" /> **hollow star**</label></div>|![[Vault Assets/Games/KTANE/Keypads/smileyface.webp]]<div><label for="k-smiley2"><input type="checkbox" id="k-smiley2" /> **smiley face**</label></div>|![[Vault Assets/Games/KTANE/Keypads/filledstar.webp]]<div><label for="k-filled"><input type="checkbox" id="k-filled" /> **filled star**</label></div>|![[Vault Assets/Games/KTANE/Keypads/omega.webp]]<div><label for="k-omega"><input type="checkbox" id="k-omega" /> **omega**</label></div>|

### Simon Says

<input type="text" placeholder="Colors" style="width: 700px;" />

![[Vault Assets/Games/KTANE/Simon Says.png|700]]

### Who's On First

![[Vault Assets/Games/KTANE/Whos On First 1.png|700]]
![[Vault Assets/Games/KTANE/Whos On First 2.png|700]]

### Memory

> [!info] Stage 1 (Position <input type="number" step="1" min="2" max="4" style="width: 32px; text-align: center;" /> | Label <input type="number" step="1" min="1" max="4" style="width: 32px; text-align: center;" />)
> Display 1: Position 2
> Display 2: Position 2
> Display 3: Position 3
> Display 4: Position 4

> [!info] Stage 2 (Position <input type="number" step="1" min="1" max="4" style="width: 32px; text-align: center;" /> | Label <input type="number" step="1" min="1" max="4" style="width: 32px; text-align: center;" />)
> Display 1: Label 4
> Display 2: Stage 1 Position
> Display 3: Position 1
> Display 4: Stage 1 Position

> [!info] Stage 3 (Label <input type="number" step="1" min="1" max="4" style="width: 32px; text-align: center;" />)
> Display 1: Stage 2 Label
> Display 2: Stage 1 Label
> Display 3: Position 3
> Display 4: Label 4

> [!info] Stage 4 (Label <input type="number" step="1" min="1" max="4" style="width: 32px; text-align: center;" />)
> Display 1: Stage 1 Position
> Display 2: Position 1
> Display 3: Stage 2 Position
> Display 4: Stage 2 Position

> [!info] Stage 5
> Display 1: Stage 1 Label
> Display 2: Stage 2 Label
> Display 3: Stage 4 Label
> Display 4: Stage 3 Label

### Morse Code

<input type="text" placeholder="Morse Code" style="width: 700px;" />

![[Vault Assets/Games/KTANE/Morse Code.png|700]]

### Complicated Wires

![[Vault Assets/Games/KTANE/Complicated Wires.png|700]]

### Wire Sequence

|<center style="color: #f00;">Red</center>|<center style="color: #f00;">Occurrence</center>|<center style="color: #00f;">Blue</center>|<center style="color: #00f;">Occurrence</center>|<center>Black</center>|<center>Occurrence</center>|
|---|---|---|---|---|---|
|<center>C</center>|<center><input type="checkbox" /></center>|<center>B</center>|<center><input type="checkbox" /></center>|<center>CUT</center>|<center><input type="checkbox" /></center>|
|<center>B</center>|<center><input type="checkbox" /></center>|<center>A or C</center>|<center><input type="checkbox" /></center>|<center>A or C</center>|<center><input type="checkbox" /></center>|
|<center>A</center>|<center><input type="checkbox" /></center>|<center>B</center>|<center><input type="checkbox" /></center>|<center>B</center>|<center><input type="checkbox" /></center>|
|<center>A or C</center>|<center><input type="checkbox" /></center>|<center>A</center>|<center><input type="checkbox" /></center>|<center>A or C</center>|<center><input type="checkbox" /></center>|
|<center>B</center>|<center><input type="checkbox" /></center>|<center>B</center>|<center><input type="checkbox" /></center>|<center>B</center>|<center><input type="checkbox" /></center>|
|<center>A or C</center>|<center><input type="checkbox" /></center>|<center>B or C</center>|<center><input type="checkbox" /></center>|<center>B or C</center>|<center><input type="checkbox" /></center>|
|<center>CUT</center>|<center><input type="checkbox" /></center>|<center>C</center>|<center><input type="checkbox" /></center>|<center>A or B</center>|<center><input type="checkbox" /></center>|
|<center>A or B</center>|<center><input type="checkbox" /></center>|<center>A or C</center>|<center><input type="checkbox" /></center>|<center>C</center>|<center><input type="checkbox" /></center>|
|<center>B</center>|<center><input type="checkbox" /></center>|<center>A</center>|<center><input type="checkbox" /></center>|<center>C</center>|<center><input type="checkbox" /></center>|

### Mazes

|<center>A1</center>|<center>A2</center>|<center>A3</center>|<center>A4</center>|<center>A5</center>|<center>A6</center>|
|---|---|---|---|---|---|
|**<center>B1</center>**|**<center>B2</center>**|**<center>B3</center>**|**<center>B4</center>**|**<center>B5</center>**|**<center>B6</center>**|
|**<center>C1</center>**|**<center>C2</center>**|**<center>C3</center>**|**<center>C4</center>**|**<center>C5</center>**|**<center>C6</center>**|
|**<center>D1</center>**|**<center>D2</center>**|**<center>D3</center>**|**<center>D4</center>**|**<center>D5</center>**|**<center>D6</center>**|
|**<center>E1</center>**|**<center>E2</center>**|**<center>E3</center>**|**<center>E4</center>**|**<center>E5</center>**|**<center>E6</center>**|
|**<center>F1</center>**|**<center>F2</center>**|**<center>F3</center>**|**<center>F4</center>**|**<center>F5</center>**|**<center>F6</center>**|

**Find Maze By Columns**
Columns 1 & 1: Maze 4
Columns 1 & 3: Maze 9
Columns 1 & 6: Maze 1
Columns 2 & 2: Maze 7
Columns 2 & 5: Maze 2
Columns 3 & 4: Maze 8
Columns 3 & 5: Maze 6
Columns 4 & 5: Maze 5
Columns 4 & 6: Maze 3

|![[Vault Assets/Games/KTANE/Mazes/maze0.svg\|256]]|![[Vault Assets/Games/KTANE/Mazes/maze1.svg\|256]]|![[Vault Assets/Games/KTANE/Mazes/maze2.svg\|256]]|
|---|---|---|
|![[Vault Assets/Games/KTANE/Mazes/maze3.svg\|256]]|![[Vault Assets/Games/KTANE/Mazes/maze4.svg\|256]]|![[Vault Assets/Games/KTANE/Mazes/maze5.svg\|256]]|
|![[Vault Assets/Games/KTANE/Mazes/maze6.svg\|256]]|![[Vault Assets/Games/KTANE/Mazes/maze7.svg\|256]]|![[Vault Assets/Games/KTANE/Mazes/maze8.svg\|256]]|

### Passwords

|Second Letter|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|
|---|---|---|---|---|---|---|
|**Third Letter**|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|<input type="text" style="width: 64px; text-align: center; text-transform: uppercase; background: none; border: none; font-weight: bold;" />|

#### First Letters


> [!list]- <input type="checkbox" style="width: 32px;" /> A
> <label for="a1"><input type="checkbox" id="a1" /> **`B O`:** ABOUT</label>
> 
> <label for="a2"><input type="checkbox" id="a2" /> **`F T`:** AFTER</label>
> 
> <label for="a3"><input type="checkbox" id="a3" /> **`G A`:** AGAIN</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> B
> <label for="b1"><input type="checkbox" id="b1"/> **`E L`:** BELOW</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> C
> <label for="c1"><input type="checkbox" id="c1" /> **`O U`:** COULD</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> E
> <label for="e1"><input type="checkbox" id="e1" /> **`V E`:** EVERY</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> F
> <label for="f1"><input type="checkbox" id="f1"/> **`I R`:** FIRST</label>
> 
> <label for="f2"><input type="checkbox" id="f2" /> **`O U`:** FOUND</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> G
> <label for="g1"><input type="checkbox" id="g1" /> **`R E`:** GREAT</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> H
> <label for="h1"><input type="checkbox" id="h1" /> **`O U`:** HOUSE</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> L
> <label for="l1"><input type="checkbox" id="l1" /> **`A R`:** LARGE</label>
> 
> <label for="l2"><input type="checkbox" id="l2"/> **`E A`:** LEARN</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> N
> <label for="n1"><input type="checkbox" id="n1"/> **`E V`:** NEVER</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> O
> <label for="o1"><input type="checkbox" id="o1"/> **`T H`:** OTHER</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> P
> <label for="p1"><input type="checkbox" id="p1"/> **`L A`:** PLACE or PLANT</label>
> 
> <label for="p2"><input type="checkbox" id="p2"/> **`O I`:** POINT</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> R
> <label for="r1"><input type="checkbox" id="r1"/> **`I G`:** RIGHT</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> S
> <label for="s1"><input type="checkbox" id="s1"/> **`M A`:** SMALL</label>
> 
> <label for="s2"><input type="checkbox" id="s2"/> **`O U`:** SOUND</label>
> 
> <label for="s3"><input type="checkbox" id="s3"/> **`P E`:** SPELL</label>
> 
> <label for="s4"><input type="checkbox" id="s4"/> **`T I`:** STILL</label>
> 
> <label for="s5"><input type="checkbox" id="s5"/> **`T U`:** STUDY</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> T
> <label for="t1"><input type="checkbox" id="t1"/> **`H E`:** THEIR or THERE or THESE</label>
> 
> <label for="t2"><input type="checkbox" id="t2"/> **`H I`:** THING or THINK</label>

> [!list]- <input type="checkbox" style="width: 32px;" /> W
> <label for="w1"><input type="checkbox" id="w1"/> **`A T`:** WATER</label>
> 
> <label for="w2"><input type="checkbox" id="w2"/> **`H E`:** WHERE</label>
> 
> <label for="w3"><input type="checkbox" id="w3"/> **`H I`:** WHICH</label>
> 
> <label for="w4"><input type="checkbox" id="w4"/> **`O R`:** WORLD</label>
> 
> <label for="w5"><input type="checkbox" id="w5"/> **`O U`:** WOULD</label>
> 
> <label for="w6"><input type="checkbox" id="w6"/> **`R I`:** WRITE</label>

### Knobs

> [!info] CURRENT
> |<input type="checkbox" style="width: 100%;"/>|<input type="checkbox" style="width: 100%;" />|<input type="checkbox" style="width: 100%;" />|<input type="checkbox" style="width: 100%;" />|<input type="checkbox" style="width: 100%;" />|<input type="checkbox" style="width: 100%;" />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;"/>|<input type="checkbox" style="width: 100%;" />|<input type="checkbox" style="width: 100%;" />|<input type="checkbox" style="width: 100%;" />|<input type="checkbox" style="width: 100%;" />|<input type="checkbox" style="width: 100%;" />|

> [!info] UP
> |<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|
>
> **<center style="color: #027AFF;">OR</center>**
> 
> |<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|

> [!info] DOWN
> |<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|
>
> **<center style="color: #027AFF;">OR</center>**
> 
> |<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|

> [!info] LEFT
> |<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|
>
> **<center style="color: #027AFF;">OR</center>**
> 
> |<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|

> [!info] RIGHT
> |<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|
>
> **<center style="color: #027AFF;">OR</center>**
> 
> |<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" disabled />|
|---|---|---|---|---|---|
|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|<input type="checkbox" style="width: 100%;" checked disabled />|<input type="checkbox" style="width: 100%;" disabled />|