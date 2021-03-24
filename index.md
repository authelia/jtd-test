# Index
<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Preview dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>

## username

<div markdown="1">
string 
{: .label .label-purple } 
required
{: .label .label-red }
</div>

Example uername config option description. 

## id

<div markdown="1">
integer
{: .label .label-purple }
optional
{: .label .label-green }
</div>

Example id config option description. 

## etc

<div markdown="1">
list
{: .label .label-purple }
semi-optional
{: .label .label-yellow }
</div>

Example etc config option description. 
