# jquery-data-handling


<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

``` <script>
$(document).ready(function(){
  $("button").click(function(){
    $("p").remove(".g");
  });
});


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






Ref: https://www.tutorialsteacher.com/jquery/jquery-dom-manipulation
