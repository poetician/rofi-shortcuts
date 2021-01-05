# rofi-shortcuts
The ultimate shortcuts cheatsheet.
This is the Poetician Edition, though most of the original is intact.
If you're starting from vanilla i3, you have a lot of configuring to do.

Dependencies
==========

  * rofi

How to install
==========
Just attach the script to a keyboard shortcut.

**If you install from AUR run**

    yay -S rofi-shortcuts-git
    rofi-shortcuts

**If you install from git run**

    # Install
    mkdir -p ~/.config/rofi/rofi-shortcuts/
    mkdir -p ~/.local/share/rofi/rofi-shortcuts/
    cp "${srcdir}"/rofi-shortcuts/rofi-shortcuts.conf ~/.config/rofi/rofi-shortcuts/rofi-shortcuts.conf
    cp "${srcdir}"/rofi-shortcuts/rofi-shortcuts.sh ~/.local/share/rofi/rofi-shortcuts/rofi-shortcuts.sh
    chmod u+x ~/.local/share/rofi/rofi-shortcuts/rofi-shortcuts.sh
    ln -sf ~/.local/share/rofi/rofi-shortcuts/rofi-shortcuts.sh ~/.local/bin/rofi-shortcuts

    # Then run rofi-shortcuts
    rofi-shortcuts


################################### TABLE OF CONTENTS ###################################
* I 3 W M
  - N a v i g a t i o n.
  - A p p l i c a t i o n s.
  - B a s e.
  - V a r i e t y.
  - M u l t i m e d i a  c o n t r o l.
* R A N G E R
  - B o o k m a r k s.
  - t a b s.
  - R a n g e r  m o v e m e n t.
  - R a n g e r  f i l e s.
  - R a n g e r  c o m m a n d s.
  - F i l e  s u b s t i t wu t i n g.
  - C u s t o m.
* S U B L I M E
* T E R M I N A T O R
  - C r e a t i o n  &  d e s t r u c t i o n.
  - N a v e g a t  i o n.
  - O r g a n i z a t i o n.
  - M i s c e l a n e o u s.
  - G r o u p i n g  &  B r o a d c a s t i n g.
* T I L I X
  - A p p l i c a t i o n.
  - t a b s (s e s s i o n s).
  - C o l u m n s.
  - R e s i z e  c o l u m n.
  - S e a r c h.
* T M U X
  - S e s s i o n s.
  - W i n d o w s.
  - P a n e s.
  - S y n c.
* V I M
  - M o v e m e n t.
  - I n s e r t  m o d e.
  - E d i t.
  - V i s u a l  m o d e.
  - V i s u a l  c o m m a n d s.
  - C u t  &  p a s t e.
  - S e a r c h  &  r e p l a c e.
  - S e a r c h  m u l t i - f i l e.
  - E x i t.
  - M u l t i  f i l e   (b u f f e r s).
  - T a b s.
  - S e s s i o n s.
  - C o m m a n d  L i n e.
  - P l u g i n s.
* B L E N D E R
  - F i l e   O p e r a t i o n s
  - E d i t i n g
* C L I P I T
* D I S C O R D
* F I R E F O X
  - C u r r e n t  p a g e.
  - T a b s.
  - H i s t o r y
  - B o o k m a r k s.
  - T o o l s.
  - P d f.
  - M i s c.
* F R A N Z
* G I M P
  - F i l e   M e n u
  - E d i t   M e n u
  - S e l e c t   M e n u
  - V i e w   M e n u
  - I m a g e   M e n u
  - L a y e r   M e n u
  - T o o l s   M e n u
   - S e l e c t
   - P a i n t
   - T r a n s f o r m
  - G e n e r a l
  - F i l t e r s   M e n u
  - W i n d o w   M e n u
  - H e l p   M e n u
* H E X C H A T
* L I B R E O F F I C E  W R I T E R
  - F u n c t i o n  k e y s.
  - B a s e.
  - P a r a g r a p h s.
  - T a b l e s.
  - M o v i n g  o b j e c t s.
* L I B R E O F F I C E  C A L C
  - N a v i g a t i o n.
  - F u n c t i o n  k e y s.
  - F o r m a t  c e l l s.
  - P i v o t  t a b l e.
* N E M O
  - G e n e r a l
  - O p e n i n g
  - T a b
  - N a v i g a t i o n
  - V i e w
  - E d i t
* R O F I
* T H U N D E R D B I R D
  - B a s e.
  - E m a i l.
  - C a l e n d a r.
  - T a s k s.
  - P l u g i n s.
* V I M I U M C
  - V i m i u m c  n a v i g a t i o n.
  - V o m n i b a r.
  - F i n d.
  - N a v i g a t i n g  h i s t o r y.
  - T a b s.

* P O E T I C I A N   A L I A S E S

* I N K S C A P E [todo]
* S C R I B U S [todo]
* S Y N F Y G  [todo]
* L I G H T W O R K S [todo]
* N A T R O N [todo]


More info
==========
* These are my personal shortcuts. All of them are defaults, but feel free to edit rofi-shortcuts.conf with your own.
* Vim shortcuts include the ones from [vim ultimate config](https://github.com/amix/vimrc).

Wanna contribute?
==========
* Pull requests with default shortcuts of missing programs are welcome.

Credits
==========
* https://github.com/hackjutsu/vim-cheatsheet
* https://devhints.io/vim
* https://gist.github.com/heroheman/aba73e47443340c35526755ef79647eb

