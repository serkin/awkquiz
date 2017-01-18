$f = function(&$arr) use(&$f) {

    foreach($arr  as &$el) {
        if(is_string($el)) $el .= '6';
        if(is_array($el)) $f($el);
    }

};


$arr = ['3','2',['5', '8', ['10','11']]];

$f($arr);

var_dump($arr);


yml_parse


https://www.toptal.com/php/interview-questions
http://stackoverflow.com/questions/8311074/how-to-call-the-current-anonymous-function-in-php
https://gyazo.com/9151408c37878e018797f369e4e7ed6e
https://github.com/danrevah/php-exercises
http://exercism.io/languages/php/exercises
