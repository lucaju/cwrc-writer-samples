<?xml version="1.0" encoding="UTF-8"?><?xml-model href="https://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_all.rng" type="application/xml" schematypens="http://relaxng.org/ns/structure/1.0"?><?xml-model href="https://www.tei-c.org/release/xml/tei/custom/schema/relaxng/tei_all.rng" type="application/xml" schematypens="https://purl.oclc.org/dsdl/schematron"?><?xml-stylesheet type="text/css" href="https://raw.githubusercontent.com/LEAF-VRE/code_snippets/refs/heads/main/CSS/leaf.css"?><TEI xmlns="http://www.tei-c.org/ns/1.0">
   <teiHeader>
      <fileDesc>
         <titleStmt>
            <title>Converted from Markdown</title>
         </titleStmt>
         <publicationStmt>
            <p>Converted using XSLT transformation</p>
         </publicationStmt>
         <sourceDesc>
            <p>This XSLT will support transformation from a Markdown file to a TEI file with TEI-All schema and correct CSS stylesheet for LEAF-Writer </p>
         </sourceDesc>
      </fileDesc>
   </teiHeader>
   <text>
      <body>
         <div>
            <head>Welcome to StackEdit</head>
            <p>Hi! I'm your first Markdown file in <hi rend="bold">StackEdit</hi>. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the <hi rend="bold">file explorer</hi> on the left corner of the navigation bar.</p>
         </div>
         <div>
            <head>Files</head>
            <p>StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible <hi rend="bold">offline!</hi>
            </p>
            <div>
               <head>Create files and folders</head>
               <p>The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the <hi rend="bold">New file</hi> button in the file explorer. You can also create folders by clicking the <hi rend="bold">New folder</hi> button.</p>
               <div>
                  <head>Switch to another file</head>
                  <p>All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.</p>
                  <div>
                     <head>Rename a file</head>
                  </div>
                  <p>You can rename the current file by clicking the file name in the navigation bar or by clicking the <hi rend="bold">Rename</hi> button in the file explorer.</p>
                  <p>##### Delete a file</p>
                  <p>You can delete the current file by clicking the <hi rend="italic">Remove</hi> button in the file explorer. The file will be moved into the <hi rend="bold">Trash</hi> folder and automatically deleted after 7 days of inactivity.</p>
                  <p>###### Export a file</p>
                  <p>You can export the current file by clicking <hi rend="bold">Export to disk</hi> in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.</p>
               </div>
            </div>
            <div>
               <head>List</head>
               <list type="unordered">
                  <item>1</item>
               </list>
               <list type="unordered">
                  <item>2</item>
               </list>
               <list type="ordered">
                  <item>1</item>
               </list>
               <list type="ordered">
                  <item>2</item>
               </list>
               <p>plain link: &lt;http://handlebarsjs.com/&gt;</p>
               <p>~~strikeout~~</p>
               <p>
                  <hi rend="bold">Bold</hi>
               </p>
               <p>
                  <hi rend="italic">italic</hi>
               </p>
               <quote>Blockquote</quote>
               <p>terwer</p>
               <p>!<ref target="https://www.homemadeinterest.com/wp-content/uploads/2022/07/Lemon-ice-box-pie_2.jpg">enter image description here</ref>
               </p>
            </div>
         </div>
         <div>
            <head>Synchronization</head>
            <p>Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your <hi rend="bold">Google Drive</hi>, your <hi rend="bold">Dropbox</hi> and your <hi rend="bold">GitHub</hi> accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.</p>
            <p>There are two types of synchronization and they can complement each other:</p>
            <list type="unordered">
               <item>The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.</item>
            </list>
            <quote>To start syncing your workspace, just sign in with Google in the menu.</quote>
            <list type="unordered">
               <item>The file synchronization will keep one file of the workspace synced with one or multiple files in <hi rend="bold">Google Drive</hi>, <hi rend="bold">Dropbox</hi> or <hi rend="bold">GitHub</hi>.</item>
            </list>
            <quote>Before starting to sync files, you must link an account in the <hi rend="bold">Synchronize</hi> sub-menu.</quote>
            <div>
               <head>Open a file</head>
               <p>You can open a file from <hi rend="bold">Google Drive</hi>, <hi rend="bold">Dropbox</hi> or <hi rend="bold"><orgName key="Game off game jam 2020 [en ligne])" ref="http://viaf.org/viaf/17172122647803162447" ana="webannotation:http://temp.lincsproject.ca/BhvwaC4U_CI">GitHub</orgName></hi> by opening the <hi rend="bold">Synchronize</hi> sub-menu and clicking <hi rend="bold">Open from</hi>. Once opened in the workspace, any modification in the file will be automatically synced.</p>
            </div>
            <div>
               <head>Save a file</head>
               <p>You can save any file of the workspace to <hi rend="bold">Google Drive</hi>, <hi rend="bold">Dropbox</hi> or <hi rend="bold">GitHub</hi> by opening the <hi rend="bold">Synchronize</hi> sub-menu and clicking <hi rend="bold">Save on</hi>. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.</p>
            </div>
            <div>
               <head>Synchronize a file</head>
               <p>Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.</p>
               <p>If you just have modified your file and you want to force syncing, click the <hi rend="bold">Synchronize now</hi> button in the navigation bar.</p>
               <quote>
                  <hi rend="bold">Note:</hi> The <hi rend="bold">Synchronize now</hi> button is disabled if you have no file to synchronize.</quote>
            </div>
            <div>
               <head>Manage file synchronization</head>
               <p>Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking <hi rend="bold">File synchronization</hi> in the <hi rend="bold">Synchronize</hi> sub-menu. This allows you to list and remove synchronized locations that are linked to your file.</p>
            </div>
         </div>
         <div>
            <head>Publication</head>
            <p>Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like <hi rend="bold">Blogger</hi>, <hi rend="bold">Dropbox</hi>, <hi rend="bold">Gist</hi>, <hi rend="bold">GitHub</hi>, <hi rend="bold">Google Drive</hi>, <hi rend="bold">WordPress</hi> and <hi rend="bold">Zendesk</hi>. With <ref target="http://handlebarsjs.com/">Handlebars templates</ref>, you have full control over what you export.</p>
            <quote>Before starting to publish, you must link an account in the <hi rend="bold">Publish</hi> sub-menu.</quote>
            <div>
               <head>Publish a File</head>
               <p>You can publish your file by opening the <hi rend="bold">Publish</hi> sub-menu and by clicking <hi rend="bold">Publish to</hi>. For some locations, you can choose between the following formats:</p>
               <list type="unordered">
                  <item>Markdown: publish the Markdown text on a website that can interpret it (<hi rend="bold">GitHub</hi> for instance),</item>
               </list>
               <list type="unordered">
                  <item>HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).</item>
               </list>
            </div>
            <div>
               <head>Update a publication</head>
               <p>After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the <hi rend="bold">Publish now</hi> button in the navigation bar.</p>
               <quote>
                  <hi rend="bold">Note:</hi> The <hi rend="bold">Publish now</hi> button is disabled if your file has not been published yet.</quote>
            </div>
            <div>
               <head>Manage file publication</head>
               <p>Since one file can be published to multiple locations, you can list and manage publish locations by clicking <hi rend="bold">File publication</hi> in the <hi rend="bold">Publish</hi> sub-menu. This allows you to list and remove publication locations that are linked to your file.</p>
            </div>
         </div>
         <div>
            <head>Markdown extensions</head>
            <p>StackEdit extends the standard Markdown syntax by adding extra <hi rend="bold">Markdown extensions</hi>, providing you with some nice features.</p>
            <quote>
               <hi rend="bold">ProTip:</hi> You can disable any <hi rend="bold">Markdown extension</hi> in the <hi rend="bold">File properties</hi> dialog.</quote>
            <div>
               <head>SmartyPants</head>
               <p>SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:</p>
               <p>| |ASCII |HTML |</p>
               <p>|----------------|-------------------------------|-----------------------------|</p>
               <p>|Single backticks|`'Isn't this fun?'` |'Isn't this fun?' |</p>
               <p>|Quotes |`"Isn't this fun?"` |"Isn't this fun?" |</p>
               <p>|Dashes |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|</p>
            </div>
            <div>
               <head>KaTeX</head>
               <p>You can render LaTeX mathematical expressions using <ref target="https://khan.github.io/KaTeX/">KaTeX</ref>:</p>
               <p>The <hi rend="italic">Gamma function</hi> satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral</p>
               <p>$$</p>
               <p>\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.</p>
               <p>$$</p>
               <quote>You can find more information about <hi rend="bold">LaTeX</hi> mathematical expressions <ref target="http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference">here</ref>.</quote>
            </div>
            <div>
               <head>CODE</head>
               <p>You can render UML diagrams using <ref target="https://mermaidjs.github.io/">Mermaid</ref>. For example, this will produce a sequence diagram:</p>
               <p>And this will produce a flow chart:</p>
               <p>`code`</p>
               <p>```</p>
               <p>Code block</p>
               <p>graph LR</p>
               <p>A[Square Rect] -- Link text --&gt; B((Circle))</p>
               <p>A --&gt; C(Round Rect)</p>
               <p>B --&gt; D{Rhombus}</p>
               <p>C --&gt; D</p>
               <p>```</p>
            </div>
         </div>
      </body>
   </text>
	<standOff type="annotation">
		
<xenoData>
			
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#">
				
<rdf:Description rdf:datatype="http://www.w3.org/TR/json-ld/" rdf:about="http://temp.lincsproject.ca/BhvwaC4U_CI">
<![CDATA[{
    "@context": [
        "http://www.w3.org/ns/anno.jsonld",
        "http://cidoc-crm.org/cidoc-crm/json-ld_context.jsonld",
        "http://wa.lincsproject.ca/v1/ns/anno.jsonld"
    ],
    "id": "http://temp.lincsproject.ca/BhvwaC4U_CI",
    "type": "Annotation",
    "motivation": "identifying",
    "created": "2026-07-07T23:36:54.093Z",
    "creator": {
        "id": "https://github.com/lucaju",
        "type": "Person",
        "name": "Luciano Frizzera",
        "label": "Luciano Frizzera"
    },
    "generator": {
        "id": "http://localhost:3000",
        "type": "Software",
        "name": "NERVE",
        "label": "NERVE",
        "softwareVersion": "0.4.0"
    },
    "target": {
        "id": "http://temp.lincsproject.ca/BhvwaC4U_CI/target/sZA11WrBF_C",
        "type": [
            "SpecificResource",
            "E73_Information_Object"
        ],
        "label": {
            "@value": "Converted from Markdown containing \"GitHub\"",
            "@lang": "en"
        },
        "format": "application/tei+xml",
        "selector": [
            {
                "id": "http://temp.lincsproject.ca/BhvwaC4U_CI/target/sZA11WrBF_C/selector/GoTEK8axhR6",
                "type": "TextPositionSelector",
                "start": 3609,
                "end": 3615,
                "label": {
                    "@value": "\"GitHub\" snippet from Converted from Markdown",
                    "@lang": "en"
                }
            },
            {
                "id": "http://temp.lincsproject.ca/BhvwaC4U_CI/target/sZA11WrBF_C/selector/FJDG55BxLL7",
                "type": "TextQuoteSelector",
                "exact": "GitHub",
                "prefix": "\n            \n               Open a file\n               You can open a file from Google Drive, Dropbox or",
                "suffix": "by opening the Synchronize sub-menu and clicking Open from",
                "label": {
                    "@value": "\"GitHub\" snippet from Converted from Markdown",
                    "@lang": "en"
                }
            },
            {
                "id": "http://temp.lincsproject.ca/BhvwaC4U_CI/target/sZA11WrBF_C/selector/UXH7ZYYmSOD",
                "type": "CssSelector",
                "value": "[ana~=webannotation:http://temp.lincsproject.ca/BhvwaC4U_CI]",
                "label": {
                    "@value": "\"GitHub\" snippet from Converted from Markdown",
                    "@lang": "en"
                }
            }
        ],
        "source": {
            "id": "https://raw.githubusercontent.com/lucaju/cwrc-writer-samples/main/nerve/test_markdown.md",
            "type": [
                "crmdig:D1_Digital_Object",
                "E33_Linguistic_Object"
            ],
            "label": {
                "@value": "Converted from Markdown",
                "@lang": "en"
            },
            "P106_is_composed_of": "http://temp.lincsproject.ca/BhvwaC4U_CI/target/sZA11WrBF_C",
            "P72_has_language": "lexvo:en",
            "P1_is_identified_by": {
                "id": "http://temp.lincsproject.ca/BhvwaC4U_CI/target/sZA11WrBF_C/source/P1_is_identified_by/-ZWGlUVUgnl",
                "type": "E33_E41_Linguistic_Appellation",
                "label": {
                    "@value": "Title of Converted from Markdown",
                    "@lang": "en"
                },
                "P190_has_symbolic_content": "Converted from Markdown"
            }
        },
        "P67_refers_to": "http://viaf.org/viaf/17172122647803162447",
        "P190_has_symbolic_content": "GitHub"
    },
    "label": {
        "@value": "\"GitHub\" identifying Game off game jam 2020 [en ligne]) in Converted from Markdown",
        "@lang": "en"
    },
    "body": {
        "id": "http://viaf.org/viaf/17172122647803162447",
        "type": "E74_Group",
        "label": "Game off game jam 2020 [en ligne])"
    }
}]]>
				
</rdf:Description>
			
</rdf:RDF>
		
</xenoData>
	</standOff>
</TEI>