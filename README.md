# goit-markup-hw-05

:root {
--primary-text-color: #212121;
--secondary-text-color: #757575;
--text-color: #ffffff;
--primary-background-color: #e5e5e5;
--secondary-background-color: #2f303a;
--background-color: #f5f4fa;
--accent-color: #2196f3;
--accent-color-hover: #188ce8;
--contacts-footer-color: rgba(255, 255, 255, 0.6);
--outline-color: #eeeeee;
--border-color: #ececec;
}
html {
box-sizing: border-box;
}

_,
_::before,
\*::after {
box-sizing: inherit;
}

.body {
color: var(--primary-text-color);
font-family: Roboto, sans-serif;
font-size: 14px;
letter-spacing: 0.03em;
}
h1,
h2,
h3,
h4,
h5,
h6,
p {
margin-top: 0px;
margin-bottom: 0px;
}

img {
display: block;
width: 100%;
height: auto;
}

ul {
list-style: none;
margin: 0px;
padding: 0px;
}

/_ Header _/

.header {
align-items: center;
border-bottom: 1px solid var(--border-color);
}

.container {
width: 1200px;
margin-left: auto;
margin-right: auto;
margin-top: 0px;
padding: 0px 15px;
}
.header\_\_box {
display: flex;
align-items: center;
}

.nav {
display: flex;
align-items: center;
}

.nav\_\_logo-link {
color: var(--accent-color);
font-family: Raleway;
font-size: 26px;
line-height: 1.19;
letter-spacing: 0.03em;
text-decoration: none;
margin-right: 93px;
padding-top: 24px;
padding-bottom: 25px;
}

.nav\_\_logo-link--black {
color: var(--primary-text-color);
}

.nav\_\_pages-list {
display: flex;
font-weight: 500;
line-height: 1.14;
letter-spacing: 0.02em;
}

.nav\_\_item {
position: relative;
padding-top: 32px;
padding-bottom: 32px;
margin-left: 50px;
}

.nav\_\_item:first-child {
margin-left: 0;
}

.nav\_\_link {
display: block;
color: var(--primary-text-color);
letter-spacing: 0.02em;
text-decoration: none;

transition-property: color;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.nav**link:hover,
.nav**link:focus {
color: var(--accent-color);
}

.nav\_\_link--active {
color: var(--accent-color);
}

.nav\_\_link--active::after {
content: "";
position: absolute;
bottom: -1px;
left: 0px;
height: 2px;
width: 100%;
background-color: var(--accent-color);
border-radius: 2px;
}

/_ Contacts _/

.contacts {
display: flex;
margin-left: auto;
font-weight: 500;
line-height: 1.14;
margin-top: 0px;
margin-bottom: 0px;
padding-left: 0px;
}

.contacts\_\_item:not(:first-child) {
margin-left: 50px;
}

.contacts\_\_link {
display: flex;
color: var(--secondary-text-color);
font-weight: 500;
letter-spacing: 0.02em;
text-decoration: none;
align-items: center;
padding-top: 32px;
padding-bottom: 32px;

transition-property: color;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.contacts**link:hover,
.contacts**link:focus {
color: var(--accent-color);
}

.contacts**link:hover .contacts**icon,
.contacts**link:focus .contacts**icon {
fill: var(--accent-color);
}

.contacts\_\_icon {
fill: var(--secondary-text-color);
margin-right: 10px;
transition-property: fill;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

/_ Hero _/

.hero-section {
max-width: 1600px;
margin: 0 auto;
background-color: var(--secondary-background-color);
text-align: center;
background-image: linear-gradient(
to right,
rgba(47, 48, 58, 0.4),
rgba(47, 48, 58, 0.4)
),
url(../images/bcgr.jpg);
background-position: center;
background-repeat: no-repeat;
background-size: cover;

padding-top: 200px;
padding-bottom: 200px;
}

.hero\_\_title {
color: var(--text-color);
font-weight: 900;
font-size: 44px;
line-height: 1.36;
letter-spacing: 0.06em;
text-align: center;
text-transform: uppercase;
margin-top: 0px;
margin-bottom: 30px;
}

.button {
background-color: var(--accent-color);
color: var(--text-color);
font-family: inherit;
font-weight: 700;
font-size: 16px;
line-height: 1.88;
cursor: pointer;
border-radius: 4px;
padding: 10px 32px;
min-width: 200px;
text-align: center;
border: none;

transition-property: background-color;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.button:hover,
.button:focus {
background-color: var(--accent-color-hover);
}

/_ Advantages _/

.pros {
padding-bottom: 0px;
}

.section {
padding-top: 94px;
padding-bottom: 94px;
}

.pros\_\_list {
display: flex;
justify-content: space-between;
}

.pros\_\_item {
width: 270px;
}

.pros\_\_icon {
display: flex;
background-color: var(--background-color);
justify-content: center;
padding-top: 25px;
padding-bottom: 25px;
margin-bottom: 30px;
}

.pros\_\_description {
font-weight: 700;
line-height: 1.14;
text-transform: uppercase;
margin-top: 0px;
margin-bottom: 10px;
}

.pros\_\_text {
color: var(--secondary-text-color);
line-height: 1.7;
margin-top: 0px;
margin-bottom: 0px;
}

/_ Services _/

.services {
background-color: var(--text-color);
}

.services\_\_section {
padding-top: 0;
padding-bottom: 94px;
}

.service**title,
.team**title,
.clients\_\_title {
font-weight: 700;
font-size: 36px;
line-height: 1.17;
text-align: center;
margin-top: 0px;
margin-bottom: 50px;
}

.service\_\_list {
display: flex;
justify-content: space-between;
}

.service\_\_item {
position: relative;
}

.service**description {
position: absolute;
bottom: 0px;
left: 0px;
width: 100%;
height: 70px;
background-color: rgba(47, 48, 58, 0.8);
font-weight: 700;
line-height: 1.17;
color: var(--text-color);
text-align: center;
text-transform: uppercase;
}
.service**text {
padding-top: 27px;
padding-bottom: 27px;
}

/_ Team _/

.team {
background-color: var(--background-color);
}

.team-members {
display: flex;
}

.team-members\_\_item {
background-color: var(--text-color);
box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 0px 1px 1px rgba(0, 0, 0, 0.14),
0px 2px 1px rgba(0, 0, 0, 0.2);
border-radius: 0px 0px 4px 4px;
margin-right: 30px;
}

.team-members\_\_item:nth-child(4n + 4) {
margin-right: 0px;
}

.team-members\_\_info {
padding-top: 30px;
padding-bottom: 30px;
}

.team-members\_\_name {
font-weight: 500;
font-size: 16px;
line-height: 1.18;
text-align: center;
margin-top: 0px;
margin-bottom: 10px;
}

.team-members\_\_position {
color: var(--secondary-text-color);
font-size: 16px;
line-height: 1.19;
text-align: center;
margin-top: 0px;
margin-bottom: 0px;
}

.social-media {
display: flex;
padding-left: 32px;
padding-right: 32px;
margin-top: 16px;
}

.social-media\_\_item {
display: flex;
margin-right: 10px;
align-items: center;
justify-content: center;
}

.social-media\_\_item:last-child {
margin-right: 0px;
}

.social-media\_\_link {
display: flex;
width: 44px;
height: 44px;
border-radius: 50%;
align-items: center;
justify-content: center;

transition-property: background-color;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.social-media**link:hover,
.social-media**link:focus {
background-color: var(--accent-color);
}

.social-media**link:hover .social-media**icon {
fill: var(--text-color);
}

.social-media\_\_icon {
fill: #afb1b8;

transition-property: fill;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

/_ Clients _/

.clients\_\_list {
display: flex;
height: 92px;
align-items: center;
justify-content: center;
}

.clients\_\_item {
margin-right: 30px;
}

.clients\_\_item:last-child {
margin-right: 0px;
}

.clients\_\_link {
display: flex;
width: 170px;
height: 92px;
border: 1px solid #afb1b8;
border-radius: 4px;
align-items: center;
justify-content: center;

transition-property: border;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.clients\_\_link:hover {
border: 1px solid var(--accent-color);
}

.clients**link:hover .clients**icon {
fill: var(--accent-color);
}

.clients\_\_icon {
fill: #afb1b8;

transition-property: fill;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

/_ Footer _/

.footer {
background-color: var(--secondary-background-color);
padding: 60px 0px;
}

.footer\_\_box {
display: flex;
align-items: flex-start;
}

.footer\_\_info {
width: 231px;
}

.footer\_\_logo {
margin-bottom: 20px;
}

.footer\_\_logo-link {
color: var(--accent-color);
font-family: Raleway;
font-size: 26px;
line-height: 1.19;
letter-spacing: 0.03em;
text-decoration: none;
margin-right: 93px;
padding-top: 24px;
padding-bottom: 25px;
}

.footer\_\_logo-link--white {
color: var(--text-color);
}

.footer\_\_address {
font-style: normal;
}

.footer\_\_address-info {
color: var(--text-color);
line-height: 1.7;
margin-bottom: 9px;
}

.footer\_\_contacts {
display: flex;
flex-direction: column;
}

.footer\_\_contacts_info {
color: var(--contacts-footer-color);
line-height: 1.7;
letter-spacing: 0.03em;
text-decoration: none;
}

.footer\_\_contacts_info:not(:last-child) {
margin-bottom: 9px;
}

.join-us {
margin-left: 70px;
}

.join-us\_\_text {
font-size: 14px;
text-transform: uppercase;
line-height: 1.17;
padding-top: 12px;
margin-bottom: 20px;
color: var(--text-color);
}

.footer\_\_social-media {
display: flex;
}

.footer\_\_social-media-item {
width: 44px;
}

.footer\_\_social-media-item:not(:last-child) {
margin-right: 10px;
}

.footer\_\_social-media-link {
display: flex;
background-color: rgba(255, 255, 255, 0.1);
justify-content: center;
align-items: center;
height: 44px;
border-radius: 50%;

transition-property: background-color;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.footer**social-media-link:hover,
.footer**social-media-link:focus {
background-color: var(--accent-color);
}

.footer\_\_icon {
fill: var(--text-color);
}

.follow {
margin-left: auto;
}
.follow\_\_text {
font-size: 14px;
text-transform: uppercase;
line-height: 1.17;
padding-top: 12px;
margin-bottom: 20px;
color: var(--text-color);
}

.follow\_\_input {
width: 358px;
height: 50px;
background-color: var(--secondary-background-color);
border: 1px solid rgba(255, 255, 255, 0.3);
border-radius: 4px;
padding: 15px 16px;
color: #ffffff;
margin-right: 12px;
}

.follow\_\_input::placeholder {
font-size: 16px;
line-height: 1.25;
}

.follow\_\_button {
display: inline-flex;
justify-content: center;
align-items: center;
background-color: var(--accent-color);
color: var(--text-color);
border: none;
border-radius: 4px;
font-weight: 700;
font-size: 16px;
line-height: 1.87;
letter-spacing: 00.03em;
width: 200px;
height: 50px;

transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.follow**button:hover,
.follow**button:focus {
background-color: var(--accent-color-hover);
}

.follow\_\_icon {
margin-left: 10px;
}

/_ Modal _/

.backdrop {
position: fixed;
top: 0;
left: 0;
width: 100%;
height: 100%;
background-color: rgba(0, 0, 0, 0.2);
opacity: 1;
transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.backdrop\_\_is-hidden {
visibility: hidden;
opacity: 0;
pointer-events: none;
}

.backdrop\_\_is-hidden .modal {
transform: translate(-50%, -50%) scale(0.7);
}

.modal {
position: absolute;
top: 50%;
left: 50%;
min-width: 528px;
min-height: 581px;
background-color: var(--text-color);
transform: translate(-50%, -50%) scale(1);
transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.close-button {
position: absolute;
top: 8px;
right: 8px;
background-color: #ffffff;
border: none;
cursor: pointer;
}

.close-button\_\_icon-box {
display: flex;
justify-content: center;
align-items: center;
width: 30px;
height: 30px;
border: 1px solid rgba(0, 0, 0, 0.1);
border-radius: 50%;
}

.close-button\_\_icon {
fill: rgba(0, 0, 0, 1);
transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.close-button:hover .close-button**icon,
.close-button:focus .close-button**icon {
fill: var(--accent-color);
}

.modal\_\_form-container {
padding: 40px;
}

.modal\_\_callback-text {
font-size: 20px;
font-weight: 700;
margin-bottom: 12px;
}

.modal\_\_form {
display: flex;
flex-direction: column;
align-items: center;
}

.modal\_\_field-container {
position: relative;
display: flex;
flex-direction: column;
margin-bottom: 10px;
}

.modal\_\_label {
position: relative;
margin-bottom: 4px;
font-size: 12px;
color: var(--secondary-text-color);
}

.modal\_\_input-container {
position: relative;
}

.modal\_\_input {
width: 448px;
height: 40px;
padding-left: 42px;
border: 1px solid rgba(33, 33, 33, 0.2);
border-radius: 4px;
overflow: hidden;
transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1),
outline 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.modal**input:focus + .modal**icon {
fill: var(--accent-color);
}

.modal\_\_input:focus {
border: 1px solid var(--accent-color);
outline: none;
}

.modal\_\_icon {
position: absolute;
top: 50%;
transform: translateY(-50%);
left: 12px;
transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.modal\_\_comments {
margin-top: 4px;
margin-bottom: 20px;
padding-left: 16px;
padding-top: 12px;
width: 448px;
height: 120px;
border: 1px solid rgba(33, 33, 33, 0.2);
border-radius: 4px;
resize: none;
transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1),
outline 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.modal\_\_comments::placeholder {
color: rgba(117, 117, 117, 0.5);
}

.modal\_\_comments:focus {
border: 1px solid var(--accent-color);
outline: none;
}

.modal\_\_checkbox {
margin-bottom: 30px;
}

.modal\_\_checkbox-label {
display: flex;
align-items: center;
position: relative;
font-size: 12px;
color: var(--secondary-text-color);
}

.modal\_\_checkbox-input {
appearance: none;
-moz-appearance: none;
-webkit-appearance: none;
padding-left: 24px;
position: absolute;
visibility: hidden;
}

.modal\_\_checkbox-icon {
position: absolute;
top: 50%;
transform: translateY(-50%);
left: 0;
width: 16px;
height: 15px;
border: 2px solid var(--primary-text-color);
border-radius: 2px;
cursor: pointer;
}

.modal\_\_policy-text {
padding-left: 24px;
font-size: 14px;
}

.modal\_\_terms {
color: var(--accent-color);
}

.modal\_\_icon-checked {
position: absolute;
top: 50%;
transform: translateY(-50%);
left: 0;
border-radius: 2px;
background-color: var(--accent-color);
opacity: 0;
cursor: pointer;
transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.modal**checkbox-input:checked ~ .modal**icon-checked {
opacity: 1;
}

.submit-button {
width: 200px;
height: 50px;
background-color: var(--accent-color);
border-radius: 4px;
border: none;
color: #ffffff;
cursor: pointer;
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
font-weight: 700;
font-size: 16px;
line-height: 1.87;
letter-spacing: 0.06em;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

.submit-button:hover,
.submit-button:focus {
background-color: var(--accent-color-hover);
}

/_ PORTFOLIO _/

.projects {
background-color: var(--text-color);
}

.projects\_\_filter {
display: flex;
justify-content: center;
margin-bottom: 50px;
}

.projects\_\_filter-item:not(:last-child) {
margin-right: 8px;
}

.projects\_\_filter-button {
background-color: var(--background-color);
color: var(--primary-text-color);
cursor: pointer;
font-family: inherit;
font-weight: 500;
font-size: 16px;
line-height: 1.63;
text-align: center;
border: none;
border-radius: 4px;
padding: 6px 22px;
transition-property: background-color, color, box-shadow;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.projects**filter-button:hover,
.projects**filter-button:focus {
box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.1), 0px 1px 2px rgba(0, 0, 0, 0.08),
0px 2px 2px rgba(0, 0, 0, 0.12);
background-color: var(--accent-color);
color: var(--text-color);
}

.card {
display: flex;
flex-wrap: wrap;
margin-left: -30px;
margin-bottom: -30px;
}

.card:nth-child(3n + 1) {
margin-left: 0px;
}

.card\_\_item {
flex-basis: calc(100% / 3 - 30px);
margin-left: 30px;
margin-bottom: 30px;
}

.card\_\_link {
display: block;
text-decoration: none;

transition-property: box-shadow;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.card**link:hover,
.card**link:focus {
box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px 4px rgba(0, 0, 0, 0.06),
1px 4px 6px rgba(0, 0, 0, 0.16);
}

.card\_\_image-container {
position: relative;
overflow: hidden;
}

.card\_\_thumb {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
background-color: rgba(33, 150, 243, 0.9);
font-size: 18px;
line-height: 1.5;
color: var(--text-color);
transform: translateY(100%);
transition-property: transform;
transition-duration: 250ms;
transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
}

.card**link:hover .card**thumb,
.card**link:focus .card**thumb {
transform: translate(0, 0);
}

.card\_\_thumb-text {
padding: 63px 24px;
}

.card\_\_description {
padding: 20px 24px;
border: 1px solid var(--outline-color);
}

.card\_\_project-name {
color: var(--primary-text-color);
font-weight: 700;
font-size: 18px;
line-height: 2;
margin-bottom: 4px;
}

.card\_\_text {
font-size: 16px;
line-height: 1.9;
}
