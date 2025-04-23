__Исправления в строчке 13__
>sregex_iterator it(text.begin() text.end(), email_pattern);
  >>sregex_iterator it(text.begin(), text.end(), email_pattern);
__Исправления в строчке 20_
 >+it;
    >>++it;
