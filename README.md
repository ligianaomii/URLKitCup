<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Kit Cups</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-transparentGray { background-color: rgba(227, 226, 224, 0); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="a52b22a1-3af8-4ee8-a2c3-ede0f88614ae" class="page sans"><header><div class="page-header-icon undefined"><img class="icon" src="Kit%20Cups%20a52b22a13af84ee8a2c3ede0f88614ae/Icon.png"/></div><h1 class="page-title">Kit Cups</h1><p class="page-description"></p></header><div class="page-body"><h2 id="3c019ce3-db17-4f60-9fd7-736805f7145e" class="">Help the dog catch cups!</h2><p id="ba293bf2-6d30-48ce-b288-92e961bcaa0f" class="">Kit Cups is an app game which the player is controlling a dog that is responsible on catching the cups and avoid the attacks from cat. On this game the more you can save, more points you gain with your owner. </p><p id="8ee62ddf-015f-49a2-a565-282f918e067a" class="">By time, the player has more cups to avoid!</p><p id="51639de2-7e4d-4b8b-b793-91e24cff8d8c" class="">
</p><h2 id="fbc0ee2b-de88-4a18-b70f-b2ee593c8607" class=""><strong>Privacy Policy</strong></h2><p id="98274cc7-0825-40d2-b0a7-5e01ae1bd264" class="">This privacy policy applies to the Catch Cups app (hereby referred to as &quot;Application&quot;) for mobile devices that was created by Lígia Naomi Nakase (hereby referred to as &quot;Service Provider&quot;) as a Freemium service. This service is intended for use &quot;AS IS&quot;.</p><p id="7f1e6858-de93-484a-8507-74b1ff0890d3" class=""><strong>Information Collection and Use</strong></p><p id="ca56230b-d08b-4518-8811-73245edf00c4" class="">The Application collects information when you download and use it. This information may include information such as</p><ul id="08a3cd40-0987-415d-81a7-991f68125eeb" class="bulleted-list"><li style="list-style-type:disc">Your device&#x27;s Internet Protocol address (e.g. IP address)</li></ul><ul id="2e907274-91c4-4989-85cd-6d9e1bf479a6" class="bulleted-list"><li style="list-style-type:disc">The pages of the Application that you visit, the time and date of your visit, the time spent on those pages</li></ul><ul id="97a1a5bc-a9ba-4d16-9d49-d00ff98060ef" class="bulleted-list"><li style="list-style-type:disc">The time spent on the Application</li></ul><ul id="9550caea-6514-4d51-9ad3-aade134d235a" class="bulleted-list"><li style="list-style-type:disc">The operating system you use on your mobile device</li></ul><p id="4f2791cf-15ec-4cfd-9484-82ec78b9ad5f" class="">The Application collects your device&#x27;s location, which helps the Service Provider determine your approximate geographical location and make use of in below ways:</p><ul id="f2f35160-9005-4086-a34d-432a982173e8" class="bulleted-list"><li style="list-style-type:disc">Geolocation Services: The Service Provider utilizes location data to provide features such as personalized content, relevant recommendations, and location-based services.</li></ul><ul id="21990375-d56e-43f2-8089-c2cc8822f7a7" class="bulleted-list"><li style="list-style-type:disc">Analytics and Improvements: Aggregated and anonymized location data helps the Service Provider to analyze user behavior, identify trends, and improve the overall performance and functionality of the Application.</li></ul><ul id="5cbf5d6c-96c9-4baf-b7d9-6cbfd2cc402e" class="bulleted-list"><li style="list-style-type:disc">Third-Party Services: Periodically, the Service Provider may transmit anonymized location data to external services. These services assist them in enhancing the Application and optimizing their offerings.</li></ul><p id="774e5521-b6c0-4874-ae6e-5af57015cf06" class="">The Service Provider may use the information you provided to contact you from time to time to provide you with important information, required notices and marketing promotions.</p><p id="8eefd11a-b3e9-424c-8a43-f68a12d13ff9" class="">For a better experience, while using the Application, the Service Provider may require you to provide us with certain personally identifiable information, including but not limited to Email, age. The information that the Service Provider request will be retained by them and used as described in this privacy policy.</p><p id="d0558896-48fd-411d-bdc3-7a1bf2c4ea71" class=""><strong>Third Party Access</strong></p><p id="617c4743-f03c-4d3d-b5fb-19a55ac1811c" class="">Only aggregated, anonymized data is periodically transmitted to external services to aid the Service Provider in improving the Application and their service. The Service Provider may share your information with third parties in the ways that are described in this privacy statement.</p><p id="c06c1e38-d865-4d34-859f-d675a8342506" class="">Please note that the Application utilizes third-party services that have their own Privacy Policy about handling data. Below are the links to the Privacy Policy of the third-party service providers used by the Application:</p><ul id="fea0b91d-fb18-4436-9539-c7680f765be6" class="bulleted-list"><li style="list-style-type:disc"><a href="https://support.google.com/admob/answer/6128543?hl=en">AdMob</a></li></ul><ul id="a15287de-ea1b-4ca0-b2b5-38e138de1a1f" class="bulleted-list"><li style="list-style-type:disc"><a href="https://firebase.google.com/support/privacy">Google Analytics for Firebase</a></li></ul><ul id="8055b11e-7982-4139-b05e-4f0bb66251eb" class="bulleted-list"><li style="list-style-type:disc"><a href="https://firebase.google.com/support/privacy/">Firebase Crashlytics</a></li></ul><ul id="c30b09ff-8ede-4492-8491-e914767d5b29" class="bulleted-list"><li style="list-style-type:disc"><a href="https://www.facebook.com/about/privacy/update/printable">Facebook</a></li></ul><p id="4f67f925-b64d-4366-b569-18c1cb040ac0" class="">The Service Provider may disclose User Provided and Automatically Collected Information:</p><ul id="e7c0797b-9961-41bb-b030-bc6459a05b28" class="bulleted-list"><li style="list-style-type:disc">as required by law, such as to comply with a subpoena, or similar legal process;</li></ul><ul id="9139b3dc-4acf-4c54-bc37-d1df63bc64e7" class="bulleted-list"><li style="list-style-type:disc">when they believe in good faith that disclosure is necessary to protect their rights, protect your safety or the safety of others, investigate fraud, or respond to a government request;</li></ul><ul id="784aeb7d-f33d-470a-af3a-5e0858f9b1e0" class="bulleted-list"><li style="list-style-type:disc">with their trusted services providers who work on their behalf, do not have an independent use of the information we disclose to them, and have agreed to adhere to the rules set forth in this privacy statement.</li></ul><p id="5870fd8b-e29f-45d1-8acb-fd6bae7b7718" class=""><strong>Opt-Out Rights</strong></p><p id="f4b4532d-f701-45ea-8546-03eadbcdb638" class="">You can stop all collection of information by the Application easily by uninstalling it. You may use the standard uninstall processes as may be available as part of your mobile device or via the mobile application marketplace or network.</p><p id="de26682a-4d94-4627-b77e-18c85abeef62" class=""><strong>Data Retention Policy</strong></p><p id="da9c0e77-f7cb-4597-a702-159a3de24781" class="">The Service Provider will retain User Provided data for as long as you use the Application and for a reasonable time thereafter. If you&#x27;d like them to delete User Provided Data that you have provided via the Application, please contact them at ligianaominakase@gmail.com and they will respond in a reasonable time.</p><p id="f48229e6-a5d2-45c0-b05c-be61277db1b7" class=""><strong>Children</strong></p><p id="ae74a7ce-fab9-4e70-a4bf-bee6ee58150c" class="">The Service Provider does not use the Application to knowingly solicit data from or market to children under the age of 13.</p><p id="b5008329-7aea-4e67-a39b-323a5c5a2418" class="">The Application does not address anyone under the age of 13. The Service Provider does not knowingly collect personally identifiable information from children under 13 years of age. In the case the Service Provider discover that a child under 13 has provided personal information, the Service Provider will immediately delete this from their servers. If you are a parent or guardian and you are aware that your child has provided us with personal information, please contact the Service Provider (ligianaominakase@gmail.com) so that they will be able to take the necessary actions.</p><p id="3721e6d9-c112-4084-854c-b374583388c5" class=""><strong>Security</strong></p><p id="230d18f3-6722-47b6-8751-e6625a943fbf" class="">The Service Provider is concerned about safeguarding the confidentiality of your information. The Service Provider provides physical, electronic, and procedural safeguards to protect information the Service Provider processes and maintains.</p><p id="cc1ebe48-e6f4-475c-949b-55bd8ee38a5d" class=""><strong>Changes</strong></p><p id="56569df9-424d-47af-bd61-708ed1cb231f" class="">This Privacy Policy may be updated from time to time for any reason. The Service Provider will notify you of any changes to the Privacy Policy by updating this page with the new Privacy Policy. You are advised to consult this Privacy Policy regularly for any changes, as continued use is deemed approval of all changes.</p><p id="71a89458-6320-4361-94dd-f67d40adeda6" class="">This privacy policy is effective as of 2024-04-08</p><p id="09a67751-1f80-4bd7-a643-d091fbe9b9e0" class=""><strong>Your Consent</strong></p><p id="c0eda0e7-6c26-4bb4-be0a-a6a536771001" class="">By using the Application, you are consenting to the processing of your information as set forth in this Privacy Policy now and as amended by us.</p><p id="bbf980ee-99d6-4c63-a9d5-b8e75a16a536" class=""><strong>Contact Us</strong></p><p id="0bd4a508-c62f-48f1-8fab-6f45af0d1e71" class="">If you have any questions regarding privacy while using the Application, or have questions about the practices, please contact the Service Provider via email at ligianaominakase@gmail.com.</p><hr id="ec03096d-3326-4315-81b1-68e689646e9d"/><h2 id="59f36d8e-0d49-42b0-b825-484931adba05" class=""><strong>Terms &amp; Conditions</strong></h2><p id="b548f0fc-d3de-430b-93b8-bbeff79da9fe" class="">These terms and conditions applies to the Catch Cups app (hereby referred to as &quot;Application&quot;) for mobile devices that was created by Lígia Naomi Nakase (hereby referred to as &quot;Service Provider&quot;) as a Freemium service.</p><p id="5cb17641-a686-4dee-aa1e-310d7a2706a9" class="">Upon downloading or utilizing the Application, you are automatically agreeing to the following terms. It is strongly advised that you thoroughly read and understand these terms prior to using the Application. Unauthorized copying, modification of the Application, any part of the Application, or our trademarks is strictly prohibited. Any attempts to extract the source code of the Application, translate the Application into other languages, or create derivative versions are not permitted. All trademarks, copyrights, database rights, and other intellectual property rights related to the Application remain the property of the Service Provider.</p><p id="85aa513a-b8d7-4842-9631-374587f9fe08" class="">The Service Provider is dedicated to ensuring that the Application is as beneficial and efficient as possible. As such, they reserve the right to modify the Application or charge for their services at any time and for any reason. The Service Provider assures you that any charges for the Application or its services will be clearly communicated to you.</p><p id="a768c75e-ec3e-4a1e-a2b6-f773ee33673b" class="">The Application stores and processes personal data that you have provided to the Service Provider in order to provide the Service. It is your responsibility to maintain the security of your phone and access to the Application. The Service Provider strongly advise against jailbreaking or rooting your phone, which involves removing software restrictions and limitations imposed by the official operating system of your device. Such actions could expose your phone to malware, viruses, malicious programs, compromise your phone&#x27;s security features, and may result in the Application not functioning correctly or at all.</p><p id="d5283d01-ba6e-49b4-beaa-9bd7d6500b1e" class="">Please note that the Application utilizes third-party services that have their own Terms and Conditions. Below are the links to the Terms and Conditions of the third-party service providers used by the Application:</p><ul id="7bcd8413-70fa-41ae-8b34-5b71ac86ee71" class="bulleted-list"><li style="list-style-type:disc"><a href="https://developers.google.com/admob/terms">AdMob</a></li></ul><ul id="75c4ee28-a8ed-4a02-bc5f-a9afa087163b" class="bulleted-list"><li style="list-style-type:disc"><a href="https://www.google.com/analytics/terms/">Google Analytics for Firebase</a></li></ul><ul id="8642faa1-dfa3-4e08-9a46-43b904438be9" class="bulleted-list"><li style="list-style-type:disc"><a href="https://firebase.google.com/terms/crashlytics">Firebase Crashlytics</a></li></ul><ul id="4a6f7f6e-f381-4dd8-943c-19ea1ec5ff09" class="bulleted-list"><li style="list-style-type:disc"><a href="https://www.facebook.com/legal/terms/plain_text_terms">Facebook</a></li></ul><p id="ff8c7796-c596-4ef8-8719-12c618ae233e" class="">Please be aware that the Service Provider does not assume responsibility for certain aspects. Some functions of the Application require an active internet connection, which can be Wi-Fi or provided by your mobile network provider. The Service Provider cannot be held responsible if the Application does not function at full capacity due to lack of access to Wi-Fi or if you have exhausted your data allowance.</p><p id="109b6403-60a4-4d58-b048-02c6552f6b52" class="">If you are using the application outside of a Wi-Fi area, please be aware that your mobile network provider&#x27;s agreement terms still apply. Consequently, you may incur charges from your mobile provider for data usage during the connection to the application, or other third-party charges. By using the application, you accept responsibility for any such charges, including roaming data charges if you use the application outside of your home territory (i.e., region or country) without disabling data roaming. If you are not the bill payer for the device on which you are using the application, they assume that you have obtained permission from the bill payer.</p><p id="b0486dc9-3b07-4b52-a2db-21aac52a83f8" class="">Similarly, the Service Provider cannot always assume responsibility for your usage of the application. For instance, it is your responsibility to ensure that your device remains charged. If your device runs out of battery and you are unable to access the Service, the Service Provider cannot be held responsible.</p><p id="8432f167-6b65-4497-886a-b1004885054d" class="">In terms of the Service Provider&#x27;s responsibility for your use of the application, it is important to note that while they strive to ensure that it is updated and accurate at all times, they do rely on third parties to provide information to them so that they can make it available to you. The Service Provider accepts no liability for any loss, direct or indirect, that you experience as a result of relying entirely on this functionality of the application.</p><p id="9a5a7ee6-d798-44ca-898c-cc30464036da" class="">The Service Provider may wish to update the application at some point. The application is currently available as per the requirements for the operating system (and for any additional systems they decide to extend the availability of the application to) may change, and you will need to download the updates if you want to continue using the application. The Service Provider does not guarantee that it will always update the application so that it is relevant to you and/or compatible with the particular operating system version installed on your device. However, you agree to always accept updates to the application when offered to you. The Service Provider may also wish to cease providing the application and may terminate its use at any time without providing termination notice to you. Unless they inform you otherwise, upon any termination, (a) the rights and licenses granted to you in these terms will end; (b) you must cease using the application, and (if necessary) delete it from your device.</p><p id="0fd903ce-aaa4-4f96-8157-dd3b0203f449" class=""><strong>Changes to These Terms and Conditions</strong></p><p id="dc31fbce-1d9a-47aa-a9d2-fe06b39f66a9" class="">The Service Provider may periodically update their Terms and Conditions. Therefore, you are advised to review this page regularly for any changes. The Service Provider will notify you of any changes by posting the new Terms and Conditions on this page.</p><p id="d2bcc0ce-0126-469a-b983-bdb0a6571f3e" class="">These terms and conditions are effective as of 2024-04-08</p><p id="9d1de1ad-ab9f-41d3-9008-315b7030b071" class=""><strong>Contact Us</strong></p><p id="a16b05bb-3a05-46c2-8ce2-30a4924724c1" class="">If you have any questions or suggestions about the Terms and Conditions, please do not hesitate to contact the Service Provider at ligianaominakase@gmail.com.</p><p id="515df075-99e6-4526-8ea8-b56ac4abdf08" class="">
</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
