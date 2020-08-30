<?php
/*
Plugin Name: なりかくんウィルス
Description: なりかくんウィルスに感染させます。
Author: なりかくん
Version: 1.0
Author URI: https://narikakun.net/
*/
add_filter('the_content', function($content) {
    $content = str_replace('は', 'なりかくん', $content);
    $content = str_replace('で', 'なりにゃん', $content);
    $content = str_replace('へ', 'なりわん', $content);
    $content = str_replace('、', 'なりか様', $content);
    $content = str_replace('。', 'なりかちゃん', $content);
    $content = '<a href="https://narikakun.net/"><img src="https://narikakun.net/wp-content/uploads/2020/08/narikakun-virus.png"></a>' . $content;
    return $content;
});
?>
