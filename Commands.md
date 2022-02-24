# 4_Narzedzia_Developerskie

Komenda do instalacji i uruchomienie html-valid:

globalnie: npm install -g html-validate
lokalnie: npm install --save-dev html-validate
sprawdzenie html: html-validate src/\*_/_.html

Błędy:

bartoszciomcia@Bartoszs-MacBook-Pro 4_Narzedzia_Developerskie % html-validate *.html

/Volumes/Mac/Programowanie/Bootcamp-Full-Stack-Plus-2022-01/4_Narzedzia_Developerskie/index.html
    1:1   warning  Usage of deprecated rule "void"                                          deprecated-rule
    5:25  warning  Expected omitted end tag <meta> instead of self-closing element <meta/>  void
    5:25  error    Expected omitted end tag <meta> instead of self-closing element <meta/>  void-style
    6:56  warning  Expected omitted end tag <meta> instead of self-closing element <meta/>  void
    6:56  error    Expected omitted end tag <meta> instead of self-closing element <meta/>  void-style
    7:73  warning  Expected omitted end tag <meta> instead of self-closing element <meta/>  void
    7:73  error    Expected omitted end tag <meta> instead of self-closing element <meta/>  void-style
   13:49  warning  Expected omitted end tag <link> instead of self-closing element <link/>  void
   13:49  error    Expected omitted end tag <link> instead of self-closing element <link/>  void-style
   14:49  warning  Expected omitted end tag <link> instead of self-closing element <link/>  void
   14:49  error    Expected omitted end tag <link> instead of self-closing element <link/>  void-style
   27:34  error    Mismatched close-tag, expected '</a>' but found '</li>'                  close-order
   27:39  error    Mismatched close-tag, expected '</li>' but found '</a>'                  close-order
   27:43  error    Mismatched close-tag, expected '</ul>' but found '</li>'                 close-order
   28:12  error    Element <li> is not permitted as content in <div>                        element-permitted-content
   29:10  error    Mismatched close-tag, expected '</div>' but found '</ul>'                close-order
   30:8   error    Mismatched close-tag, expected '</section>' but found '</div>'           close-order
   31:6   error    Mismatched close-tag, expected '</header>' but found '</section>'        close-order
   35:8   error    <button> is missing required "type" attribute                            element-required-attributes
   36:10  error    Element <a> is not permitted as descendant of <button>                   element-permitted-content
   40:4   error    Mismatched close-tag, expected '</body>' but found '</header>'           close-order
   42:4   error    Element <main> is not permitted as content in <html>                     element-permitted-content
   50:14  error    Attribute "src" has invalid value ""                                     attribute-allowed-values
   50:32  warning  Expected omitted end tag <img> instead of self-closing element <img/>    void
   50:32  error    Expected omitted end tag <img> instead of self-closing element <img/>    void-style
   59:14  error    Attribute "src" has invalid value ""                                     attribute-allowed-values
   59:32  warning  Expected omitted end tag <img> instead of self-closing element <img/>    void
   59:32  error    Expected omitted end tag <img> instead of self-closing element <img/>    void-style
   68:14  error    Attribute "src" has invalid value ""                                     attribute-allowed-values
   68:32  warning  Expected omitted end tag <img> instead of self-closing element <img/>    void
   68:32  error    Expected omitted end tag <img> instead of self-closing element <img/>    void-style
  131:14  error    <button> is missing required "type" attribute                            element-required-attributes
  148:14  error    <button> is missing required "type" attribute                            element-required-attributes
  165:14  error    <button> is missing required "type" attribute                            element-required-attributes
  198:10  error    <button> is missing required "type" attribute                            element-required-attributes
  203:4   error    Element <footer> is not permitted as content in <html>                   element-permitted-content
  213:2   error    Mismatched close-tag, expected '</html>' but found '</body>'             close-order
  215:2   error    Unexpected close-tag, expected opening tag                               close-order

✖ 38 problems (29 errors, 9 warnings)

More information:
  https://html-validate.org/rules/deprecated-rule.html
  https://html-validate.org/rules/void.html
  https://html-validate.org/rules/void-style.html
  https://html-validate.org/rules/close-order.html
  https://html-validate.org/rules/element-permitted-content.html
  https://html-validate.org/rules/element-required-attributes.html
  https://html-validate.org/rules/attribute-allowed-values.html
