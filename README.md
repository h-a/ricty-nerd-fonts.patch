# ricty-nerd-fonts.patch

This patch is to generate Ricty-nerd-font from Inconsolata-nerd-font and Migu 1M.

Usage:

1. Install FontForge from https://fontforge.github.io/ or by a package manager  

2. Get Inconsolata Nerd Font (3.000)  
   from https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Inconsolata  

3. Get Migu 1M (2015.0712 or later)  
   from http://mix-mplus-ipa.osdn.jp/  

4. Get ricty_generator.sh  
   from https://rictyfonts.github.io/  

5. Apply a patch  
   % patch < ricty_generator.patch  

6. Run script by  
     % ./ricty_generator.sh auto  
   or by  
     % ./ricty_generator.sh InconsolataNerdFont-{Regular,Bold}.ttf migu-1m-{regular,bold}.ttf  
