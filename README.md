# openparlgc-docs

We need better docs about the open data available in Canada's Parliament.

This is a stub which can be used to provide other links and documentation which can be maintained by the community.  

Search MP's to CSV/XML
  http://www.parl.gc.ca/parliamentarians/en/members
  
List of constituencies in CSV/XML
  http://www.parl.gc.ca/Parliamentarians/en/constituencies
  
Hansard & Committees in XML
  http://www.parl.gc.ca/HousePublications/Publication.aspx?Language=E&Mode=1&Parl=42&Ses=1&DocId=8512294&xml=true
  
MP Roles & Committee Membership to XML
  http://www.parl.gc.ca/parliamentarians/en/membership
  
Expenditures by Member to XML
  http://www.parl.gc.ca/PublicDisclosure/MemberExpenditures.aspx?Id=MER2016Q1&Language=E
  
Cabinet to XML
  http://www.parl.gc.ca/parliamentarians/en/ministries

Petition Search CSV/XML
  https://petitions.parl.gc.ca/en/Petition/Search?category=All&text=peace

  
Research Publications RSS Feed
  http://www.lop.parl.gc.ca/About/Library/VirtualLibrary/ResearchPublications-e.asp?Language=E
  
Schedule of All Meetings RSS Feed
  http://www.parl.gc.ca/SenCommitteeBusiness/AllMeetings.aspx?Language=E&pastMeetings=1
  

Our Commons - odata 
  http://ourcommons.ca/odata

The House of Commons OData service provide access to various data sets including:
  • Bills
  • Members Of Parliament Info • Motions
  • Committee Meetings • Decisions (votes)
  • Sessions

Tools such as LINQpad can be used to query OData services. https://www.linqpad.net/

http://ourcommons.ca/odata/MpInfos?SearchText='%‘
http://ourcommons.ca/odata/MpInfos?PersonId=88892

Roles
http://www.parl.gc.ca/Parliamentarians/en/members/88892/ExportRoles? current=True&output=XML

Interventions in the Chamber
http://www.parl.gc.ca/Parliamentarians/en/publicationsearch? per=88892&pubType=37&xml=1

Interventions in Committee
http://www.parl.gc.ca/Parliamentarians/en/publicationsearch? per=88892&pubType=37&xml=1

Voting Record
http://www.parl.gc.ca/Parliamentarians/en/members/88892/ExportVotes?output=XML

Bills Sponsored
http://www.parl.gc.ca/LegisInfo/Result.aspx?SponsorPersonId=88892&download=xml


Bills

http://www.parl.gc.ca/LegisInfo/Home.aspx? ParliamentSession=42-1&download=xml
http://www.parl.gc.ca/LegisInfo/BillDetails.aspx?BillId=8269852&download=xml
http://www.parl.gc.ca/HousePublications/Publication.aspx? DocId=8280564&Language=E&xml=true http://www.parl.gc.ca/HousePublications/Publication.aspx?

Hansard

http://www.parl.gc.ca/HousePublications/Publication.aspx?DocId=8365546&Language=E&xml=true
http://www.parl.gc.ca/HousePublications/Publication.aspx?Pub=Hansard&Doc=72&Parl=42&Ses=1&Language=E&xml=true

Petitions

https://petitions.parl.gc.ca/en/Petition/Search?Category=All&output=xml

Data Formats - XML (Documents & Data Sets)

Official House of Commons publications are published in the XML format (using custom schemas). This includes documents such as Bills, Journals, Debates (Hansard) and Committee Proceedings.
Complex data sets (and data sets that were published before the adoption of OData) are exposed using XML.

OData (Data Sets)

OData (Open Data Protocol) is an OASIS standard that defines a set of best practices for building and consuming RESTful APIs. As of 2015, the House of Commons has adopted OData v4.0 for exposing data sets.
Documentation: http://docs.oasis-open.org/odata/odata/v4.0/.
