# Decascade
<sub>A humble <a href="https://github.com/andreasgrafen/cascade">cascade</a> fork for TST for my personal use</sub>
<br>
<p style="text-align:center">
<img src="https://github.com/Sororfortuna/decascade/assets/18470725/78cca087-ab11-4bdb-9091-ff6f9c3085cd" width="800">
</p>

TST css:
```css
:root {
	--sidebar-collapsed-width: 48px;
	--transition-duration: 0.2s;
	--transition-ease: ease-out;
}

/* Show title of unread tabs with red and italic font */
:root.sidebar tab-item.unread .label-content {
	font-weight: bold !important;
}

tab-item tab-item-substance {
	padding: 6px;
}

tab-item .background {
	top: 0;
	bottom: 0;
	left: 0;
	right: 0;
}

tab-item tab-favicon {
	order: 10 !important;
	margin-left: 18px;
	margin-right: 16px;
	transition: var(--transition-duration) var(--transition-ease);
}

tab-item tab-closebox {
	transition: margin-right var(--transition-duration) var(--transition-ease);
	padding: 0;
	margin-right: -32px;
}

tab-item:hover tab-closebox {
	margin-right: 0px;
}

#tabbar {
	padding: 0px 10px 10px 10px;
	scrollbar-color: #ffffff20 transparent;
}

.newtab-button {
	padding: 10px;
}

.after-tabs .newtab-button-box {
	padding: 0px 10px 10px 10px;
}

.newtab-action-selector-anchor {
	margin: 0 10px 10px 0;
}
```
