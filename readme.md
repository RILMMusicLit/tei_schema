
The RILM TEI schema is based on the full [TEI](http://www.tei-c.org/) schema. 

TEI was chosen for two main reasons: (1) It is an established standard. Having the content marked up according to well known, standard schema will help to preserve them in the event that they are separated from their current system; and (2) It is flexible. TEI P5 has, built in, the means to mark up reference works like MGG, but it could also be used for monographs, periodicals, or other types of text. It can also accommodate works published in in different languages, as well as historical texts, and textual commentary. Other schemas that were examined were more limited to specific document types or functions.

Our customization had the following goals: (1) Pare down the schema so there are fewer choices for casual user; (2) Add custom elements, such as `<pitch>`, `<opus>`, and `<instrumentation>`; (3) Assign and limit attrubute values to make markup easier. In the current EGRET editorial system, FontoXML can be configured to limit some of the user's attribute and element options. It may thus be possible to broaden the schema in the future. (We should keep in mind that TEI documents are edited outside of EGRET: both at the original point of conversion and when changes need to be made in the shadow database.) Ticket for that: https://github.com/RILMMusicLit/tei_schema/issues/6
  
RILM uses one schema, but different products can use different versions of that schema. It is important that any change made to the schema will not preclude compatibility with any other (current or future) RILM products.

This is where the schema is maintained and developed, but the product-specific versions actually in use are kept in submodules in https://github.com/RILMMusicLit/rilm.info-ft/tree/master/schema

