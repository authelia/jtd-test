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

## Example One

### username

<div markdown="1">
string 
{: .label .label-config .label-purple }
default:apple
{: .label .label-config .label-blue }
required
{: .label .label-config .label-red }
</div>

Example uername config option description. 

### id

<div markdown="1">
integer
{: .label .label-config .label-purple }
default:5
{: .label .label-config .label-blue }
optional
{: .label .label-config .label-green }
</div>

Example id config option description. 

### etc

<div markdown="1">
list
{: .label .label-config .label-purple }
default:[]
{: .label .label-config .label-blue }
semi-optional
{: .label .label-config .label-yellow }
</div>

Example etc config option description. 

## Example Two

### username

<div markdown="1">
type:string 
{: .label .label-config .label-purple } 
default:apple
{: .label .label-config .label-blue }
required:yes
{: .label .label-config .label-red }
</div>

Example uername config option description. 

### id

<div markdown="1">
type:integer
{: .label .label-config .label-purple }
default:5
{: .label .label-config .label-blue }
required:no
{: .label .label-config .label-green }
</div>

Example id config option description. 

### etc

<div markdown="1">
type:list
{: .label .label-config .label-purple }
default:[]
{: .label .label-config .label-blue }
required:situational
{: .label .label-config .label-yellow }
</div>

Example etc config option description. 

## Example Three

### username
<div markdown="1">
type: string 
{: .label .label-config .label-purple } 
default: apple
{: .label .label-config .label-blue }
required: yes
{: .label .label-config .label-red }
</div>

Example uername config option description. 

### id
<div markdown="1">
type: integer
{: .label .label-config .label-purple }
default: 5
{: .label .label-config .label-blue }
required: no
{: .label .label-config .label-green }
</div>

Example id config option description. 

### etc
<div markdown="1">
type: list
{: .label .label-config .label-purple }
default: []
{: .label .label-config .label-blue }
required: situational
{: .label .label-config .label-yellow }
</div>

Example etc config option description. 

### blank default
<div markdown="1">
type: string
{: .label .label-config .label-purple }
default: ""
{: .label .label-config .label-blue }
required: situational
{: .label .label-config .label-yellow }
</div>

Example etc config option description. 

## Example Four

### username

<div markdown="1">
TYPE: string 
{: .label .label-config .label-purple } 
DEFAULT: apple
{: .label .label-config .label-blue }
REQUIRED: yes
{: .label .label-config .label-red }
</div>

Example uername config option description. 

### id

<div markdown="1">
TYPE: integer
{: .label .label-config .label-purple }
DEFAULT: 5
{: .label .label-config .label-blue }
REQUIRED: no
{: .label .label-config .label-green }
</div>

Example id config option description. 

### etc

<div markdown="1">
TYPE: list
{: .label .label-config .label-purple }
DEFAULT: []
{: .label .label-config .label-blue }
REQUIRED: situational
{: .label .label-config .label-yellow }
</div>

Example etc config option description. 
