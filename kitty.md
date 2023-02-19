**KITTY (terminale)**

*cp /usr/share/doc/kitty/kitty.conf ~/.config/kitty/*

*micro ~/.config/kitty/kitty.conf*

background_opacity 0.8

font_family Terminus

bold_font auto

italic_font auto

bold_italic_font auto

font_size 11.0

tab_bar_min_tabs 1

tab_bar_edge bottom

tab_bar_style powerline

tab_powerline_style slanted

tab_title_template {title}{' :{}:'.format(num_windows) if num_windows > 1 else ''}
