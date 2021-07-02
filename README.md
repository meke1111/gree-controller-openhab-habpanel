# Gree controller openhab-habpanel

<h2>Prerequisites</h2>
- installed Openhab (3.0 is prefered) <br>
- installed <a title="openhab-habpanel-theme-matrix" href="https://github.com/pmpkk/openhab-habpanel-theme-matrix">openhab-habpanel-theme-matrix</a><br>
- installed Gree binding <br>
- items, things, map like the Gree Binding document are used<br>
- enabled HABPanel<br>

<h2>Folder structure</h2>
In my setup:<br>
- /static/ = /etc/openhab/html<br>
- /static/icon/ = /etc/openhab/html/icon/<br>

<h2>Installation</h2>
- No necessary to install this controller.<br>

<h2>Setup</h2>
1) Copy gree_habpanel_icon.svg file to <i>/static/icon/</i> folder.<br>
2) Copy gree_msz.css file to <i>/static/</i> folder. <br>
3) Add a new "Template widget" in your control panel (or create a new widget) at HABPanel.<br>
4) Copy the control code from <i>Gree_control.tpl.html</i> file to the field of the Teplate's edit (widget's code) window.<br>
 
<h2>Function:</h2>
- All Aircondition control commands are in the code, meaning there is no need to add new rules to <i>*.rules</i> file;<br>
- The Aircondition can be switched on/off by button next to this name. <br>
- The second knob is used for set and show target temperature.<br>
- The Airconditon mode can be seleted by single selection. The selected mode will be showed by small at this slection field and large icon at below.<br>
- The zero value of the fan means automatic set up.<br>
- The vertical and horizontal swing can be adjusted with the icons. 
