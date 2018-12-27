<p>Keep this panel at the top of Existing Sections or it will display in Summon</p>
<p>Click Edit, then click Tools &gt; Source to view the Javascript customizations</p>
<script>var sections = $(".customSections").children("ul").first();
sections.children("li").first().css("display", "none");

//Expands any facets that are not expanded by default (e.g. Library Location and Language facets)
$('h3 a').ready(function() {
$('h3 a[aria-pressed=false]').click();
// If you only want to expand a specific facet replace the above line with something like this (example for Library Location, note that this won't work if you change the label of this facet to something else): $('a:contains("Library Location")')[0].click();
});

//Add any additional Javascript you would like to apply here</script>
