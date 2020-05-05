<div class="invisiblepanel">
<script>$("div.invisiblepanel").parent().parent().css("display", "none");
/*
This JavaScript will add a COVID-19 alert link for All Print Items Currently Unavailable Link on print books. Code addapted from California College of the Arts Libraries
*/ 
$(document).ready(function(){
            $(".Z3988").parent().each(function() {
                    var a = angular.element(this).scope().doc,
                        b = a.content_type;
                    a && ("Book" === b || "Video Recording" === b || "Film" === b || "Music Score" === b) && $(this).append("<span class=\"availability\" style=\"margin-left:1em\"><a class=\"availabilityLink printUnavailable\" href=\"https://www.colorado.edu/libraries/spring20-updates#Remote-Access-to-Libraries-Collections\" target=\"_blank\"><i class=\"uxf-icon uxf-attention\"></i> All Physical Items Currently Unavailable</a></span>")
                
            })
});</script>
</div>
