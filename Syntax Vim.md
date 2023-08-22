
#### Lưu và thoát

-   Để thoát khỏi vi/vim ta dùng: ” **:q** “
-   Để lưu file trong vi/vim ta dùng: ” **:w** “
-   Để lưu file và thoát ta dùng: ” **:wq** “
-   Để thoát và không lưu ta dùng: ” **:q!** “

**Lưu ý: để thực hiện được các command đầu tiên chúng ta phải thoát chế độ edit bằng phím Esc.(Hầu hết các thao tác trong vi/vim đều phải thoát chế độ edit trước khi thực hiện)**

##### Di chuyển con trỏ

Có 2 cách để di chuyển con trỏ trong vi/vim
-   Sử dụng phím **mũi tên**
-   Sử dụng phím ” **h, j, k, l** “

##### Xóa một dòng

##### Xóa một hoặc nhiều từ

##### Xóa một hoặc nhiều từXóa 

## Vim Shortcuts List/VIM Hotkey List  
### Cursor Movements 
1. **h -** moving the cursor to the left
2. **j -** moving the cursor down
3. **k -** moving the cursor up
4. **l -** moving the cursor to the right right
5. **H -** Jumping directly on the top of the screen
6. **M -** Jumping in the middle of the screen
7. **L -** Jumping directly to the bottom of the screen
8. **w -** Jumping on the start of a written word
9. **e -** Jumping toward the end of a written word
10. **Ctrl + e -** Moving the screen down by one line without the use of a cursor
11. **Ctrl + y -** Moving the screen up by one line without making use of the cursor
12. **Ctrl + b -** Moving one fullscreen forward
13. **Ctrl + f -** Moving one fullscreen backward
14. **Ctrl + d -** Moving ½ fullscreen forward 
### Insert mode - inserting/appending text
1. **i -** Inserting before the cursor 
2. **I -** inserting at the beginning of a line 
3. **a -** inserting after the cursor
4. **A -** inserting at the end of the line
5. **o -** Opening new lines below the selected line
6. **O -** Opening new lines above the selected line
7. **ea -** inserting at the end of the selected word
8. **Ctrl + h -** deleting characters before the cursor 
9. **Ctrl + w -** deleting words before the cursor 
10. **Ctrl + j -** Creating a new line while inserting a new mode
11. **Ctrl + t -** Moving right with one line shift width
12. **Ctrl + d -** Moving left with one line shift width
13. **Ctrl + ox -** Quickly access normal mode for executing any normal mode command
14. **Esc -** Exiting the insert mode 

### Working with multiple files

1. **:e[dit] file -** Editing files in new buffer
2. **:bn[ext] -** Jumping to the next buffer
3. **:bp[revious] -** Jumping back to the previous buffer 
4. **:bd[elete] -** Deleting a buffer 
5. **:b[uffer]# -** Hoping directly to a buffer through the index 
6. **:b[uffer] file -** Hopping to a buffer through the file 
7. **Ctrl + ws -** Splitting the Window
8. **Ctrl + wv -** Vertical splitting of the Window 
9. **Ctrl + ww -** Switching between the windows
10. **Ctrl + wq -** Quitting Window
11. **Ctrl + wx -** Exchanging the current Window with the next Window
12. **Ctrl + w= -** Adjusting the height and width of all the Windows as the same
13. **Ctrl + wh -** Jumping the cursor to the next Window
14. **Ctrl + wl -** Jumping the cursor to the next Window
15. **Ctrl + wj -** Jumping the cursor to the Window present below
16. **Ctrl + wk -** Jumping the cursor to the Window present above 
17. **Ctrl + wH -** Making selected Window expand to the full screen 
18. **Ctrl + wJ -** Making selected Window expand to the full screen at the right bottom

### Cut and paste

1. **yy -** (Copy command) pull a single line
2. **2yy -** (Copy command) pull two lines
3. **yw -** (Copy command) pull the characters of the words below the cursor to start the next position 
4. **yiw -** (Copy command) Pull the words below the cursor 
5. **yaw -** (Copy command) Pull the words selected with the cursor and add space 
6. **p -** (paste command) paste from clipboard after the cursor position
7. **P -** (paste command) paste from the clipboard before the cursor position
8. **gP -** (paste command) paste content before cursor and leave cursor after newly added text
9. **dd -** (cut command) deleting a line
10. **2dd -** (cut command) deleting two lines
11. **dw -** (cut command) deleting the characters of the word selected from the cursor 
12. **diw -** (cut command) deleting words selected through the cursor 
13. **D -** (cut command) deleting text at the end of the selected line
14. **x -** (cut command) deleting characters

### Editing 

1. **r -** replacing only one character 
2. **R -** replacing more a single characters
3. **J -** Joining below the line with the current one, along with adding one-line space between them 
4. **gJ** - Joining below the line with the current one without adding any space 
5. **cc -** Changing the entire line 
6. **C -** Changing at the end of a line
7. **ciw -** Replacing an entire word
8. **cw or ce -** Replacing at the end of a word
9. **s -** deleting characters along with substituting its text
10. **S -** Deleting lines along with substituting their text
11. **xp -** Trasposing 2 letters 
12. **u -** Undo

### Search and replace 

1. **/pattern -** Quickly search patterns
2. **?pattern -** Quickly search backward for a pattern
3. **n -** Repeating search in a similar direction 
4. **N -** Repeating searches in different directions 
5. **:%s/old/new/g -** Replacing old contents with the new ones all over the file
6. **:noh[lsearch] -** Removing highlights from search matches 

If you want to know more about the VIM search command, check out [this post](https://monovm.com/blog/how-to-search-in-vim-editor/),

### Tabs

1. **:tabnew** or **:tabnew {page.words.file} -** Opening a new file in a new tab
2. **Ctrl + wT -** Moving the current split Window into an old tab
3. **gt** or **:tabn[ext] -** Moving to a next tab
4. **gT** or **:tabp[revious] -** Moving back to the previous tab
5. **:tabm[ove] # -** Moving selected tab to a pointed location 
6. **:tabc[lose] -** Closing the current tab
7. **:tabo[nly] -** Closing every tab except the selected one
