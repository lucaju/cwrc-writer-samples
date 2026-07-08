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
         <p>Sample Document Title Created from original research by members of CWRC/CSÉC unless otherwise noted. # <persName key="Russell, Bertrand, 1872-1970." ref="http://viaf.org/viaf/36924137" ana="webannotation:http://temp.lincsproject.ca/U8FO172TBPb">Bertrand Russell</persName> to Patricia Spence - October 21, 1935 <hi rend="italic">Note: Bad writing due to shaky train In train Oslo to Bergen </hi> 21.10.35Dearest - I have had no letter from you since I left Stockholm, but I had a nice one from John in an envelope you had sent him. I had sent him one addressed to Copenhagen but he hadn't used it. When I reached Oslo yesterday evening, Brynjulf Bull should have been there to meet me, but wasn't. He is not on the telephone, so I took a taxi to his address, which turned out to be a students' club with no one about on Sundays, so I went to a hotel feeling rather non-plussed. But presently he turned up. He had got the [Page: 2] time of my arrival wrong, and whenwhen he had found he had missed me he phoned to every hotel in Oslo till he hit on the right one. He left me at 10, and then I had to do a Sunday Referee article. Today my journey lasts from 9 till 9 - fortunately one of the most beautiful railway journeys in the world. Tomorrow I lecture at Bergen to the Anglo-Norwegian Society. Next day I go back to Oslo, lecture there Fri. and Sat. and then start for home via Bergen. [Page: 3] Bull is a nice young man but incompetent - can't quite stand the communists, but finds the socialists too mild. I am unhappily wondering what you are feeling about me. I love you very much -B</p>
      </body>
   </text>
	<standOff type="annotation">
		
<xenoData>
			
<rdf:RDF xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#">
				
<rdf:Description rdf:datatype="http://www.w3.org/TR/json-ld/" rdf:about="http://temp.lincsproject.ca/U8FO172TBPb">
<![CDATA[{
    "@context": [
        "http://www.w3.org/ns/anno.jsonld",
        "http://cidoc-crm.org/cidoc-crm/json-ld_context.jsonld",
        "http://wa.lincsproject.ca/v1/ns/anno.jsonld"
    ],
    "id": "http://temp.lincsproject.ca/U8FO172TBPb",
    "type": "Annotation",
    "motivation": "identifying",
    "created": "2026-07-08T01:26:38.018Z",
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
        "id": "http://temp.lincsproject.ca/U8FO172TBPb/target/k7mQl8wO-FA",
        "type": [
            "SpecificResource",
            "E73_Information_Object"
        ],
        "label": {
            "@value": "Converted from Markdown containing \"Bertrand Russell\"",
            "@lang": "en"
        },
        "format": "application/tei+xml",
        "selector": [
            {
                "id": "http://temp.lincsproject.ca/U8FO172TBPb/target/k7mQl8wO-FA/selector/NMyfMG_EPQr",
                "type": "TextPositionSelector",
                "start": 120,
                "end": 136,
                "label": {
                    "@value": "\"Bertrand Russell\" snippet from Converted from Markdown",
                    "@lang": "en"
                }
            },
            {
                "id": "http://temp.lincsproject.ca/U8FO172TBPb/target/k7mQl8wO-FA/selector/-L2d7LSq_c_",
                "type": "TextQuoteSelector",
                "exact": "Bertrand Russell",
                "prefix": " #",
                "suffix": "to Patricia Spence - October 21, 1935 Note: Bad writing due to shaky train In train Oslo to Bergen  21",
                "label": {
                    "@value": "\"Bertrand Russell\" snippet from Converted from Markdown",
                    "@lang": "en"
                }
            },
            {
                "id": "http://temp.lincsproject.ca/U8FO172TBPb/target/k7mQl8wO-FA/selector/VdXxb5g2nK8",
                "type": "CssSelector",
                "value": "[ana~=webannotation:http://temp.lincsproject.ca/U8FO172TBPb]",
                "label": {
                    "@value": "\"Bertrand Russell\" snippet from Converted from Markdown",
                    "@lang": "en"
                }
            }
        ],
        "source": {
            "id": "https://raw.githubusercontent.com/lucaju/cwrc-writer-samples/main/nerve/Bertrand%20Russell%20to%20Patricia%20Spence%20(letter).md",
            "type": [
                "crmdig:D1_Digital_Object",
                "E33_Linguistic_Object"
            ],
            "label": {
                "@value": "Converted from Markdown",
                "@lang": "en"
            },
            "P106_is_composed_of": "http://temp.lincsproject.ca/U8FO172TBPb/target/k7mQl8wO-FA",
            "P72_has_language": "lexvo:en",
            "P1_is_identified_by": {
                "id": "http://temp.lincsproject.ca/U8FO172TBPb/target/k7mQl8wO-FA/source/P1_is_identified_by/z8ifQha98rJ",
                "type": "E33_E41_Linguistic_Appellation",
                "label": {
                    "@value": "Title of Converted from Markdown",
                    "@lang": "en"
                },
                "P190_has_symbolic_content": "Converted from Markdown"
            }
        },
        "P67_refers_to": "http://viaf.org/viaf/36924137",
        "P190_has_symbolic_content": "Bertrand Russell"
    },
    "label": {
        "@value": "\"Bertrand Russell\" identifying Russell, Bertrand, 1872-1970. in Converted from Markdown",
        "@lang": "en"
    },
    "body": {
        "id": "http://viaf.org/viaf/36924137",
        "type": "E21_Person",
        "label": "Russell, Bertrand, 1872-1970.",
        "description": "Russell, Bertrand"
    }
}]]>
				
</rdf:Description>
			
</rdf:RDF>
		
</xenoData>
	</standOff>
</TEI>