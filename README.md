# jquery-data-handling


<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

``` <script>
$(document).ready(function(){
  $("button").click(function(){
    $("p").remove(".g");
  });
});

https://www.w3schools.com/jquery/jquery_dom_remove.asp
https://stackoverflow.com/questions/47824/how-do-you-remove-all-the-options-of-a-select-box-and-then-add-one-option-and-se


function(json) {
    var options = [];
    $('#org_category').html('');  // Set the Dropdown as Blank before new Data
    options.push('<option>-- Select Category --</option>');
    $.each(JSON.parse(json), function(i, item) {
        options.push($('<option/>',
        {
           value: item.org_name, text: item.org_name
        }));
    });
    $('#org_category').append(options);  // Set the Values to Dropdown
}


</script> 

```
```
$("button").click(function(){
  $("p").toggle();
});

$(selector).val(value)

$("#hide").click(function(){
    $("p").hide();
  });
  $("#show").click(function(){
    $("p").show();
  });
  
  ```
  
  
  https://www.w3schools.com/tags/att_option_disabled.asp#:~:text=The%20disabled%20attribute%20is%20a,a%20checkbox%2C%20etc.).
  https://www.geeksforgeeks.org/jquery-set-the-value-of-an-input-text-field/
  https://learn.jquery.com/using-jquery-core/faq/how-do-i-get-the-text-value-of-a-selected-option/
  
  https://stackoverflow.com/questions/20976497/jquery-change-event-on-dropdown
  https://www.w3schools.com/jquery/jquery_hide_show.asp#:~:text=Syntax%3A,%22fast%22%2C%20or%20milliseconds.
  https://www.w3schools.com/jquery/tryit.asp?filename=tryjquery_hide_show
  https://www.geeksforgeeks.org/jquery-set-the-value-of-an-input-text-field/






Ref: https://www.tutorialsteacher.com/jquery/jquery-dom-manipulation
 1. https://stackoverflow.com/questions/170986/what-is-the-best-way-to-add-options-to-a-select-from-a-javascript-object-with-jq
 2. github : https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
 3. https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks
