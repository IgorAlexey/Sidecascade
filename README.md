# Side-cascade
<sub>Firefox stylesheets for my personal use.
<br>
<br>
Essentially, this is a fusion between <a href="https://github.com/refact0r/sidefox">Sidefox</a> and [Lepton](https://github.com/black7375/Firefox-UI-Fix), resulting in a combination that I value highly.
<br>
<p style="text-align:center">
<img src="https://github.com/Sororfortuna/decascade/assets/18470725/78cca087-ab11-4bdb-9091-ff6f9c3085cd" width="800">
</p>

This was originally a <a href="https://github.com/andreasgrafen/cascade">Cascade</a> fork

## Setup
1. set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true` in **about:config**
2. Copy the contents of this repository to your profile folder's root directory (find it in **about:profiles**)
3. Set your Tree-style-tab CSS to the Stylesheet below.
<details>
<summary><b>Click to Expand</b> Stylesheet</summary>

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

tab-item {
	overflow: hidden;
}

tab-item tab-item-substance {
	padding: 6px !important;
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

.after-tabs button:hover::before {
	bottom: 0;
	left: 0;
	right: 0;
	top: 0;
}

.after-tabs .newtab-button-box {
	background: var(--theme-colors-sidebar);
}

#tabbar-container > .after-tabs .newtab-button-box {
	padding: 0 10px 10px 10px;
}

.newtab-action-selector-anchor {
	margin: 0 10px 10px 0;
}
```

</details>

4. Restart your Firefox
