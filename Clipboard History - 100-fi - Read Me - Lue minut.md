By running the commands, you can get the whole extension translated.
Suorittamalla komennot, saat koko laajennuksen käännettyä.

cd ~/.local/share/gnome-shell/extensions/clipboard-history@alexsaveau.dev/

sed -i 's/Search clipboard history.../Selaa leikepöydän historiaa.../' extension.js

sed -i 's/Toggle private mode/Yksityistila/' prefs.js

sed -i 's/Max clipboard history size (MiB)/Leikepöydän historian enimmäiskoko (MiB)/' prefs.js

sed -i 's/Ask for confirmation before clearing history/Kysy vahvistus ennen historian tyhjentämistä/' prefs.js

Log out/in.
Kirjaudu ulos/sisään.

#####################################################

#####################################################

#: extension.js:113
#, fuzzy
msgid "Search clipboard history..."
msgstr "Selaa leikepöydän historiaa..."

#: prefs.js:120
#, fuzzy
msgid ""
"Toggle private mode"
msgstr "Yksityistila"

#: prefs.js:139
#, fuzzy
msgid ""
"Max clipboard history size (MiB)"
msgstr "Leikepöydän historian enimmäiskoko (MiB)"

#: prefs.js:154
#, fuzzy
msgid ""
"Ask for confirmation before clearing history"
msgstr "Kysy vahvistus ennen historian tyhjentämistä"

#####################################################
x                                                x
 #### #   # ###      ###   ####  #### # #    ####
 #    ##  # #  #    #   #  #     #    # #    #
 ##   # # # #   #  #     # ##    ##   # #    ##
 #    #  ## #  #    #   #  #     #    # #    #
 #### #   # ###      ###   #     #    # #### ####
x                                                x
#####################################################

