# php_lang_vivid
Check language and show translated content

             <?php
                $lang = substr($_SERVER['HTTP_ACCEPT_LANGUAGE'], 0, 2); 
                if($lang=='es'){
                    echo "Español"; //Spanish
                }elseif($lang=='ko'){
                    echo "한국어"; //Korean
                }elseif($lang=='nl'){
                    echo "Nederlands"; //Dutch- Netherland
                }elseif($lang=='de'){
                    echo "Deutsche"; //German
                }elseif($lang=='zh'){
                    echo "中文"; //Chinese-China
                }elseif($lang=='ru'){
                    echo "русский"; //Russian
                }elseif($lang=='ar'){
                    echo "عربى"; //Arabic
                }elseif($lang=='fr'){
                    echo "français"; //French
                }elseif($lang=='ja'){
                    echo "日本"; //Japanese
                }elseif($lang=='it'){
                    echo "italiano"; //Italian
                }elseif($lang=='pt'){
                    echo "Português"; //Portuguese
                }elseif($lang=='id'){
                    echo "bahasa Indonesia"; //Indonesian
                }else{
                    echo "English"; //else:English
                }
             ?>

