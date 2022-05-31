/*
 * Page breaks
  page-break-after: always;
  page-break-before: always;
  page-break-inside: avoid;
*/
// sass-lint:disable-all
@page {
  margin-top: 1em;
  margin-bottom: 1em;
}
a {
  text-decoration: none !important;
}
a[href]:after {
  content: none !important;
}

#main, .full-main, #sidebar-first {
  padding-top: 0 !important;
}

.block-local-tasks-block,
.block-system-breadcrumb-block,
.off-canvas-content > header,
.off-canvas-content > .region-meta-header-wrapper,
#sliding-popup,
.block-contact-block,
.bottom-bar,
#toolbar-administration,
#block-vip-main-menu{
  display: none !important;
  visibility: hidden !important;
}

img:-moz-broken {
  visibility: hidden !important;
  display: none !important;
}

.contextual-region {
  table-layout: fixed;
}

.node-title {
  border-style: double;

}

table {
  border-collapse: collapse//separate//; - különálló négyzetek
  //border-spacing: 4px;//               - különálló négyzetek
}

thead {
  background-color: rgb(205, 197, 197);
}

th,
td,
.field-label {
  border: 1px solid #000000;
  padding: 10px 110px;
  width: 400px;
  text-align: center;
}

.field-label {

  width: 1625px;
}

th {
  font-weight: bold;
}
.node-title {

  &::before {
    display: inline-block;
    padding: 10px;
    border-radius: 30px;
    background-color:rgb(67, 91, 214);
    content: url("../images/footer-logo.svg");
    
  }
  
}

.field-items {
  color: rgb(255, 0, 0);
}
