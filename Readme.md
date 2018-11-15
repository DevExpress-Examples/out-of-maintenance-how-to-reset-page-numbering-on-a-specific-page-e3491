<!-- default file list -->
*Files to look at*:

* [Form1.cs](./CS/Form1.cs) (VB: [Form1.vb](./VB/Form1.vb))
* [StringSample.cs](./CS/StringSample.cs) (VB: [StringSample.vb](./VB/StringSample.vb))
<!-- default file list end -->
# How to reset page numbering on a specific page


<p>This example illustrates how to reset page numbering (in the document header) on a specific page. To achieve this goal, add a new <a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument9553"><u>Section</u></a> to a document and set its PageNumbering.Start property (see <a href="http://documentation.devexpress.com/#CoreLibraries/DevExpressXtraRichEditAPINativeSectionPageNumbering_Starttopic"><u>SectionPageNumbering.Start</u></a>) to 1. Note that page numbering is setup by creating a <a href="http://documentation.devexpress.com/#WindowsForms/CustomDocument9716"><u>PAGE</u></a> field in the document header. The entire document is generated programmatically.</p>

<br/>


