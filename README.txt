This is a fork from displaytag v 1.2 svn trunk, modified to 

- correctly manage pagination update in case of keepStatus = true and possible deletion of records in the list

- read pagesize from a property to use the same value for all tables without the need to specify the attribute in display:table tag
(however, to not implement pagination, a pagesize attribute must be specified and the value must be set to -1)

- correctly manage the export of full list in case of external pagination
 
