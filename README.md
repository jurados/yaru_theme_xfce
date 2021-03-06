# Yaru Theme for XFCE
This is a guide, initially to me, for install the yaru theme over a xfce, specifically the xubuntu distribution.


### Default Xubuntu theme 20.04
![](https://149366088.v2.pressablecdn.com/wp-content/uploads/2019/04/xubuntu-19.04-desktop-screenshot-750x422.jpg)
![](https://149366088.v2.pressablecdn.com/wp-content/uploads/2020/01/Xubuntu-20.04-dark-theme-greybird-1536x864.jpg)
Images obtained from [omg!ubuntu!](https://www.omgubuntu.co.uk/2020/01/xubuntu-dark-theme-20-04).

### Yaru theme Ubuntu
![](https://raw.githubusercontent.com/ubuntu/yaru/master/.github/readme_pics/nautilus-light.png)
![](https://raw.githubusercontent.com/ubuntu/yaru/master/.github/readme_pics/nautilus-dark.png)
Images obtained from [github](https://github.com/ubuntu/yaru).


Firstly, I recommend review this [github](https://github.com/ubuntu/yaru). This will be the main github to make the theme's changing.
Secondly, I recommend review these two pages:  [page_one](https://www.linuxuprising.com/2021/09/ubuntus-yaru-theme-gets-official.html) and [page_two](https://news.itsfoss.com/yaru-xfce-support/). There, both realize a brief tutorial code by code (step by step) to obtain the ***yaru theme***, the default theme of Ubuntu+20. In brief these are the codes.

```
sudo apt install git meson sassc libglib2.0-dev libxml2-utils
git clone https://github.com/ubuntu/yaru
cd yaru && meson build -Dxfwm4=true && sudo ninja -C build
install
```


## Console color

General
- **Text color:** #F7F4DB
- **Background color:** #300A24
- **Tab Active:** #0F4999

Custom colors: Only select `Text selection color` and `Bold text color`
- **Text selection color:** #163B59 and no other.
- **Bold text color:** #FFFFFF

Palette: I'm dividing this section by rows.
|  | color 1 | color 2 | color 3 | color 4 | color 5 | color 6 | color 7 | color 8 |
|--|--|--|--|--|--|--|--|--|
|row_1| #2E3436 | #CC0000 | #4E9A06 | #C4A000 | #3465A4 | #75507B | #06989A | #D3D7CF | 
|row_2| #555753 | #EF2929 | #8AE234 | #FCE94F | #729FCF | #AD7FA8 | #34E2E2 | #EEEEEC |

Also you sould select the option `Show bold text in bright colors`.

Finall terminal theme.
![](https://i.blogs.es/56c9ee/cd/1366_2000.jpg)
Image obtained from [ganbeta](https://www.genbeta.com/linux/linux-paso-a-paso-los-cinco-comandos-para-la-terminal-que-todo-usuario-de-ubuntu-debe-conocer).
