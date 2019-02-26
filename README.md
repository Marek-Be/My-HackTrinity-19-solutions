# My-HackTrinity-19-solutions

Denovo 1 - To find this flag I used radare2 to find a list of all functions. I noticed that there was a function called "sym.print_flag", I decided to run the binary with gdb and used Ctrl-C to get back into the gdb menu and branch the the address of that function. When I did I got the flag: HackTrinity{n0_drm_1s_uNBreAkable}

Bunny - I opened the file using VLC media player and it popped up the title which was: "SGFja1RyaW5pdHl7MXRzX24wdF9qVXNUX2FiMHV0X3RoM192MWRlMH0K". I eventually tried using a base64 decoder and got the flag: HackTrinity{1ts_n0t_jUsT_ab0ut_th3_v1de0}

Book of Kells 1 - I simply opened the url with tor browser and found the flag: HackTrinity{welcome_to_the_dark_web_its_rather_boring_tbqhwy}

Trinity Ball 1 - I went to the website and after I couldn't purchase more than one ticket I inspected the element of the website. I then ran the function "addItemToBasket(1)" in the browser console. I then got the flag : HackTrinity{client_side_is_best_side}

Dust in your eyes? - When I opened the text file we get the following string: "‌‌‌‌‍‌‬‌HackTrinity{Look‌‌‌‌‍‬‌‍‌‌‌‌‍‬‌﻿ ‌‌‌‌‍‬‬﻿‌‌‌‌‍‍‍‌‌‌‌‌‍﻿‌‬‌‌‌‌‍‬‬‍‌‌‌‌‍‬﻿‬closer‌‌‌‌‍‬‬‍ ‌‌‌‌‍﻿‍‌‌‌‌‌‍﻿‬‍‌‌‌‌‍﻿‬﻿‌‌‌‌‍‬‌﻿‌‌‌‌‍‬﻿‌the‌‌‌‌‍‬‍‍ flag‌‌‌‌‍‬‌‍‌‌‌‌‍‬﻿‬ ‌‌‌‌‌‬‌‌‌‌‌‌‍﻿‬‍is‌‌‌‌‍‬﻿﻿‌‌‌‌‍﻿‍‍‌‌‌‌‍﻿‌‬‌‌‌‌‌‬‌‌ ‌‌‌‌‍‬‍﻿‌‌‌‌‍‬﻿‌‌‌‌‌‍‬‌‍here}‌‌‌‌‍﻿‌﻿‌‌‌‌‍﻿‌﻿‌‌‌‌‍‬‍‍‌‌‌‌‍﻿‌﻿‌‌‌‌‍﻿﻿‍". Eventually I found that the string had a huge number of 0-width characters in it. I then used a decoder and got the flag: HackTrinity{clean your glasses}

Who Am I? - I added this number on whatsapp and got the following flag: HackTrinity{maybe_we_should_e2e_encrypt_profile_pics}

Brew - I figured out that a .cia file format is used for Nintendo 3DS games. I got a citra emulator and ran the file, getting the flag: HackTrinity{DoNt_g1v3_yoUr_wii_Orange_JuiCe}

Turing-Lang - You are provided the following code: "#/#######>&<\># /###>&&&&<\>& && &&&&&&&& >#/###>&<\># #/###>&<\>& ######### &&&&& ##### &&&&&&&&&&& &&&&& && /#>&&&&&<\>&& ########## &&&&& &&&&&&&&&&& # &&&&&& &/#>&&&<\> &&&&&&&&&&&& &&& & &&&&&&&& ##/#>&&&<\> &&&&&&&&&&&&& ####### &&&&&&&&&  /###>&<\># &&&& ". I figured out this was brainFuck and when I ran it I got the flag: HackTrinity{i_dont_know_lenny}
You must replace the following things to compile it:
/,[;
\\,];
\#,-;
&,+;
(space),.;

Big Chungus + 3 - Similarly to the last one this is also brainfuck, we replace the following things and run it in a brainFuck compiler:
chunga,-;
karen,+;
big,>;
chunky,.;
ricardo,];
fudd,[;
chungus,<;
This gets us the flag: HackTrinity{TheseMemesAreSo0O0oLastMonth}

Zippy - We are provided a zipped file. When I opened it with my zip manager it told me the file inside was 1.7 Peta Bytes big. This is clearly impossible and I eventually figured out to edit the hex values of the zipped file with the pk zip file format to change the size to something managable. I then got the flag: HackTrinity{g0ttA_l0ve_pkz1p_l1m1tati0ns}
