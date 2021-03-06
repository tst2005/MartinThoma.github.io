---
layout: post
title: Colors in Vim
author: Martin Thoma
date: 2013-04-09 17:36:31.000000000 +02:00
category: Code
tags: Vim
featured_image: 2012/01/vim-logo.png
---
<h2>ANSI Color codes</h2>

<table>
  <tr>
    <td style="background: black;color:white">0</td>
    <td style="background: maroon;color:white">1</td>
    <td style="background: green;color:white">2</td>
    <td style="background: olive;color:white">3</td>
    <td style="background: navy;color:white">4</td>
    <td style="background: purple;color:white">5</td>
    <td style="background: teal;color:white">6</td>
    <td style="background: silver;color:black">7</td>
  </tr>
</table>

<h2>256 colors</h2>
You might need to <code>set t_Co=256</code>.

<table>
<tr>
<td style="background:#000000">x016_Grey0</td>
<td style="background:#00005f">x017_NavyBlue</td>
<td style="background:#000087">x018_DarkBlue</td>
<td style="background:#0000af">x019_Blue3</td>
</tr>
<tr>
<td style="background:#0000d7">x020_Blue3</td>
<td style="background:#0000ff">x021_Blue1</td>
<td style="background:#005f00">x022_DarkGreen</td>
<td style="background:#005f5f">x023_DeepSkyBlue4</td>
</tr>
<tr>
<td style="background:#005f87">x024_DeepSkyBlue4</td>
<td style="background:#005faf">x025_DeepSkyBlue4</td>
<td style="background:#005fd7">x026_DodgerBlue3</td>
<td style="background:#005fff">x027_DodgerBlue2</td>
</tr>
<tr>
<td style="background:#008700">x028_Green4</td>
<td style="background:#00875f">x029_SpringGreen4</td>
<td style="background:#008787">x030_Turquoise4</td>
<td style="background:#0087af">x031_DeepSkyBlue3</td>
</tr>
<tr>
<td style="background:#0087d7">x032_DeepSkyBlue3</td>
<td style="background:#0087ff">x033_DodgerBlue1</td>
<td style="background:#00af00">x034_Green3</td>
<td style="background:#00af5f">x035_SpringGreen3</td>
</tr>
<tr>
<td style="background:#00af87">x036_DarkCyan</td>
<td style="background:#00afaf">x037_LightSeaGreen</td>
<td style="background:#00afd7">x038_DeepSkyBlue2</td>
<td style="background:#00afff">x039_DeepSkyBlue1</td>
</tr>
<tr>
<td style="background:#00d700">x040_Green3</td>
<td style="background:#00d75f">x041_SpringGreen3</td>
<td style="background:#00d787">x042_SpringGreen2</td>
<td style="background:#00d7af">x043_Cyan3</td>
</tr>
<tr>
<td style="background:#00d7d7">x044_DarkTurquoise</td>
<td style="background:#00d7ff">x045_Turquoise2</td>
<td style="background:#00ff00">x046_Green1</td>
<td style="background:#00ff5f">x047_SpringGreen2</td>
</tr>
<tr>
<td style="background:#00ff87">x048_SpringGreen1</td>
<td style="background:#00ffaf">x049_MediumSpringGreen</td>
<td style="background:#00ffd7">x050_Cyan2</td>
<td style="background:#00ffff">x051_Cyan1</td>
</tr>
<tr>
<td style="background:#5f0000">x052_DarkRed</td>
<td style="background:#5f005f">x053_DeepPink4</td>
<td style="background:#5f0087">x054_Purple4</td>
<td style="background:#5f00af">x055_Purple4</td>
</tr>
<tr>
<td style="background:#5f00d7">x056_Purple3</td>
<td style="background:#5f00ff">x057_BlueViolet</td>
<td style="background:#5f5f00">x058_Orange4</td>
<td style="background:#5f5f5f">x059_Grey37</td>
</tr>
<tr>
<td style="background:#5f5f87">x060_MediumPurple4</td>
<td style="background:#5f5faf">x061_SlateBlue3</td>
<td style="background:#5f5fd7">x062_SlateBlue3</td>
<td style="background:#5f5fff">x063_RoyalBlue1</td>
</tr>
<tr>
<td style="background:#5f8700">x064_Chartreuse4</td>
<td style="background:#5f875f">x065_DarkSeaGreen4</td>
<td style="background:#5f8787">x066_PaleTurquoise4</td>
<td style="background:#5f87af">x067_SteelBlue</td>
</tr>
<tr>
<td style="background:#5f87d7">x068_SteelBlue3</td>
<td style="background:#5f87ff">x069_CornflowerBlue</td>
<td style="background:#5faf00">x070_Chartreuse3</td>
<td style="background:#5faf5f">x071_DarkSeaGreen4</td>
</tr>
<tr>
<td style="background:#5faf87">x072_CadetBlue</td>
<td style="background:#5fafaf">x073_CadetBlue</td>
<td style="background:#5fafd7">x074_SkyBlue3</td>
<td style="background:#5fafff">x075_SteelBlue1</td>
</tr>
<tr>
<td style="background:#5fd700">x076_Chartreuse3</td>
<td style="background:#5fd75f">x077_PaleGreen3</td>
<td style="background:#5fd787">x078_SeaGreen3</td>
<td style="background:#5fd7af">x079_Aquamarine3</td>
</tr>
<tr>
<td style="background:#5fd7d7">x080_MediumTurquoise</td>
<td style="background:#5fd7ff">x081_SteelBlue1</td>
<td style="background:#5fff00">x082_Chartreuse2</td>
<td style="background:#5fff5f">x083_SeaGreen2</td>
</tr>
<tr>
<td style="background:#5fff87">x084_SeaGreen1</td>
<td style="background:#5fffaf">x085_SeaGreen1</td>
<td style="background:#5fffd7">x086_Aquamarine1</td>
<td style="background:#5fffff">x087_DarkSlateGray2</td>
</tr>
<tr>
<td style="background:#870000">x088_DarkRed</td>
<td style="background:#87005f">x089_DeepPink4</td>
<td style="background:#870087">x090_DarkMagenta</td>
<td style="background:#8700af">x091_DarkMagenta</td>
</tr>
<tr>
<td style="background:#8700d7">x092_DarkViolet</td>
<td style="background:#8700ff">x093_Purple</td>
<td style="background:#875f00">x094_Orange4</td>
<td style="background:#875f5f">x095_LightPink4</td>
</tr>
<tr>
<td style="background:#875f87">x096_Plum4</td>
<td style="background:#875faf">x097_MediumPurple3</td>
<td style="background:#875fd7">x098_MediumPurple3</td>
<td style="background:#875fff">x099_SlateBlue1</td>
</tr>
<tr>
<td style="background:#878700">x100_Yellow4</td>
<td style="background:#87875f">x101_Wheat4</td>
<td style="background:#878787">x102_Grey53</td>
<td style="background:#8787af">x103_LightSlateGrey</td>
</tr>
<tr>
<td style="background:#8787d7">x104_MediumPurple</td>
<td style="background:#8787ff">x105_LightSlateBlue</td>
<td style="background:#87af00">x106_Yellow4</td>
<td style="background:#87af5f">x107_DarkOliveGreen3</td>
</tr>
<tr>
<td style="background:#87af87">x108_DarkSeaGreen</td>
<td style="background:#87afaf">x109_LightSkyBlue3</td>
<td style="background:#87afd7">x110_LightSkyBlue3</td>
<td style="background:#87afff">x111_SkyBlue2</td>
</tr>
<tr>
<td style="background:#87d700">x112_Chartreuse2</td>
<td style="background:#87d75f">x113_DarkOliveGreen3</td>
<td style="background:#87d787">x114_PaleGreen3</td>
<td style="background:#87d7af">x115_DarkSeaGreen3</td>
</tr>
<tr>
<td style="background:#87d7d7">x116_DarkSlateGray3</td>
<td style="background:#87d7ff">x117_SkyBlue1</td>
<td style="background:#87ff00">x118_Chartreuse1</td>
<td style="background:#87ff5f">x119_LightGreen</td>
</tr>
<tr>
<td style="background:#87ff87">x120_LightGreen</td>
<td style="background:#87ffaf">x121_PaleGreen1</td>
<td style="background:#87ffd7">x122_Aquamarine1</td>
<td style="background:#87ffff">x123_DarkSlateGray1</td>
</tr>
<tr>
<td style="background:#af0000">x124_Red3</td>
<td style="background:#af005f">x125_DeepPink4</td>
<td style="background:#af0087">x126_MediumVioletRed</td>
<td style="background:#af00af">x127_Magenta3</td>
</tr>
<tr>
<td style="background:#af00d7">x128_DarkViolet</td>
<td style="background:#af00ff">x129_Purple</td>
<td style="background:#af5f00">x130_DarkOrange3</td>
<td style="background:#af5f5f">x131_IndianRed</td>
</tr>
<tr>
<td style="background:#af5f87">x132_HotPink3</td>
<td style="background:#af5faf">x133_MediumOrchid3</td>
<td style="background:#af5fd7">x134_MediumOrchid</td>
<td style="background:#af5fff">x135_MediumPurple2</td>
</tr>
<tr>
<td style="background:#af8700">x136_DarkGoldenrod</td>
<td style="background:#af875f">x137_LightSalmon3</td>
<td style="background:#af8787">x138_RosyBrown</td>
<td style="background:#af87af">x139_Grey63</td>
</tr>
<tr>
<td style="background:#af87d7">x140_MediumPurple2</td>
<td style="background:#af87ff">x141_MediumPurple1</td>
<td style="background:#afaf00">x142_Gold3</td>
<td style="background:#afaf5f">x143_DarkKhaki</td>
</tr>
<tr>
<td style="background:#afaf87">x144_NavajoWhite3</td>
<td style="background:#afafaf">x145_Grey69</td>
<td style="background:#afafd7">x146_LightSteelBlue3</td>
<td style="background:#afafff">x147_LightSteelBlue</td>
</tr>
<tr>
<td style="background:#afd700">x148_Yellow3</td>
<td style="background:#afd75f">x149_DarkOliveGreen3</td>
<td style="background:#afd787">x150_DarkSeaGreen3</td>
<td style="background:#afd7af">x151_DarkSeaGreen2</td>
</tr>
<tr>
<td style="background:#afd7d7">x152_LightCyan3</td>
<td style="background:#afd7ff">x153_LightSkyBlue1</td>
<td style="background:#afff00">x154_GreenYellow</td>
<td style="background:#afff5f">x155_DarkOliveGreen2</td>
</tr>
<tr>
<td style="background:#afff87">x156_PaleGreen1</td>
<td style="background:#afffaf">x157_DarkSeaGreen2</td>
<td style="background:#afffd7">x158_DarkSeaGreen1</td>
<td style="background:#afffff">x159_PaleTurquoise1</td>
</tr>
<tr>
<td style="background:#d70000">x160_Red3</td>
<td style="background:#d7005f">x161_DeepPink3</td>
<td style="background:#d70087">x162_DeepPink3</td>
<td style="background:#d700af">x163_Magenta3</td>
</tr>
<tr>
<td style="background:#d700d7">x164_Magenta3</td>
<td style="background:#d700ff">x165_Magenta2</td>
<td style="background:#d75f00">x166_DarkOrange3</td>
<td style="background:#d75f5f">x167_IndianRed</td>
</tr>
<tr>
<td style="background:#d75f87">x168_HotPink3</td>
<td style="background:#d75faf">x169_HotPink2</td>
<td style="background:#d75fd7">x170_Orchid</td>
<td style="background:#d75fff">x171_MediumOrchid1</td>
</tr>
<tr>
<td style="background:#d78700">x172_Orange3</td>
<td style="background:#d7875f">x173_LightSalmon3</td>
<td style="background:#d78787">x174_LightPink3</td>
<td style="background:#d787af">x175_Pink3</td>
</tr>
<tr>
<td style="background:#d787d7">x176_Plum3</td>
<td style="background:#d787ff">x177_Violet</td>
<td style="background:#d7af00">x178_Gold3</td>
<td style="background:#d7af5f">x179_LightGoldenrod3</td>
</tr>
<tr>
<td style="background:#d7af87">x180_Tan</td>
<td style="background:#d7afaf">x181_MistyRose3</td>
<td style="background:#d7afd7">x182_Thistle3</td>
<td style="background:#d7afff">x183_Plum2</td>
</tr>
<tr>
<td style="background:#d7d700">x184_Yellow3</td>
<td style="background:#d7d75f">x185_Khaki3</td>
<td style="background:#d7d787">x186_LightGoldenrod2</td>
<td style="background:#d7d7af">x187_LightYellow3</td>
</tr>
<tr>
<td style="background:#d7d7d7">x188_Grey84</td>
<td style="background:#d7d7ff">x189_LightSteelBlue1</td>
<td style="background:#d7ff00">x190_Yellow2</td>
<td style="background:#d7ff5f">x191_DarkOliveGreen1</td>
</tr>
<tr>
<td style="background:#d7ff87">x192_DarkOliveGreen1</td>
<td style="background:#d7ffaf">x193_DarkSeaGreen1</td>
<td style="background:#d7ffd7">x194_Honeydew2</td>
<td style="background:#d7ffff">x195_LightCyan1</td>
</tr>
<tr>
<td style="background:#ff0000">x196_Red1</td>
<td style="background:#ff005f">x197_DeepPink2</td>
<td style="background:#ff0087">x198_DeepPink1</td>
<td style="background:#ff00af">x199_DeepPink1</td>
</tr>
<tr>
<td style="background:#ff00d7">x200_Magenta2</td>
<td style="background:#ff00ff">x201_Magenta1</td>
<td style="background:#ff5f00">x202_OrangeRed1</td>
<td style="background:#ff5f5f">x203_IndianRed1</td>
</tr>
<tr>
<td style="background:#ff5f87">x204_IndianRed1</td>
<td style="background:#ff5faf">x205_HotPink</td>
<td style="background:#ff5fd7">x206_HotPink</td>
<td style="background:#ff5fff">x207_MediumOrchid1</td>
</tr>
<tr>
<td style="background:#ff8700">x208_DarkOrange</td>
<td style="background:#ff875f">x209_Salmon1</td>
<td style="background:#ff8787">x210_LightCoral</td>
<td style="background:#ff87af">x211_PaleVioletRed1</td>
</tr>
<tr>
<td style="background:#ff87d7">x212_Orchid2</td>
<td style="background:#ff87ff">x213_Orchid1</td>
<td style="background:#ffaf00">x214_Orange1</td>
<td style="background:#ffaf5f">x215_SandyBrown</td>
</tr>
<tr>
<td style="background:#ffaf87">x216_LightSalmon1</td>
<td style="background:#ffafaf">x217_LightPink1</td>
<td style="background:#ffafd7">x218_Pink1</td>
<td style="background:#ffafff">x219_Plum1</td>
</tr>
<tr>
<td style="background:#ffd700">x220_Gold1</td>
<td style="background:#ffd75f">x221_LightGoldenrod2</td>
<td style="background:#ffd787">x222_LightGoldenrod2</td>
<td style="background:#ffd7af">x223_NavajoWhite1</td>
</tr>
<tr>
<td style="background:#ffd7d7">x224_MistyRose1</td>
<td style="background:#ffd7ff">x225_Thistle1</td>
<td style="background:#ffff00">x226_Yellow1</td>
<td style="background:#ffff5f">x227_LightGoldenrod1</td>
</tr>
<tr>
<td style="background:#ffff87">x228_Khaki1</td>
<td style="background:#ffffaf">x229_Wheat1</td>
<td style="background:#ffffd7">x230_Cornsilk1</td>
<td style="background:#ffffff">x231_Grey100</td>
</tr>
<tr>
<td style="background:#080808">x232_Grey3</td>
<td style="background:#121212">x233_Grey7</td>
<td style="background:#1c1c1c">x234_Grey11</td>
<td style="background:#262626">x235_Grey15</td>
</tr>
<tr>
<td style="background:#303030">x236_Grey19</td>
<td style="background:#3a3a3a">x237_Grey23</td>
<td style="background:#444444">x238_Grey27</td>
<td style="background:#4e4e4e">x239_Grey30</td>
</tr>
<tr>
<td style="background:#585858">x240_Grey35</td>
<td style="background:#626262">x241_Grey39</td>
<td style="background:#6c6c6c">x242_Grey42</td>
<td style="background:#767676">x243_Grey46</td>
</tr>
<tr>
<td style="background:#808080">x244_Grey50</td>
<td style="background:#8a8a8a">x245_Grey54</td>
<td style="background:#949494">x246_Grey58</td>
<td style="background:#9e9e9e">x247_Grey62</td>
</tr>
<tr>
<td style="background:#a8a8a8">x248_Grey66</td>
<td style="background:#b2b2b2">x249_Grey70</td>
<td style="background:#bcbcbc">x250_Grey74</td>
<td style="background:#c6c6c6">x251_Grey78</td>
</tr>
<tr>
<td style="background:#d0d0d0">x252_Grey82</td>
<td style="background:#dadada">x253_Grey85</td>
<td style="background:#e4e4e4">x254_Grey89</td>
<td style="background:#eeeeee">x255_Grey93</td>
</tr>
</table>

<h2>Colorize Vim</h2>
You can highlight your current line by adding the following line to your <strong>.vimrc</strong>:
<code>hi CursorLine cterm=NONE ctermbg=187</code>

The following line will use color 0 (black) for the text color of the line numbers and color 187 (see above) for the background.
<code>highlight LineNr ctermfg=0 ctermbg=187</code>
