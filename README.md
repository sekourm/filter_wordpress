# filter_wordpress

<pre>
function test($param) {
	echo $param;
}

add_filter( 'name_of_filter', 'test',1,3);

do_action('name_of_filter','i work !'); // return 'i work !'
</pre>
