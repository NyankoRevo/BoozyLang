BoozyLang (codename: 醪糟)
=========
BozzyLang is a little language that compiles into C.

Bozzylang also helps you writtring C extsions for Ruby/Python in a way that more-like your favorite language.

##hello world
There are two style of `hello world` hell.

    #= include <stdio.h>
    def int main(void)
      printf "Hello, world\n"
      return 0;
    end


    #= include <stdio.h>
    int main(void)->
      printf "Fuck world\n"
      return 0;

