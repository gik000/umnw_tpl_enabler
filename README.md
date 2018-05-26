"# umnw_tpl_enabler" 

Allows to override templates in whatever Drupal 7 module.

Add a tpl_enabler hook like this:

<pre>
// mymodule hook
function mymodule_tpl_enabler(){
  // Nothing to declare here
  // we just need the function signatures.
}
</pre>