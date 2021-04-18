SQL Dependency is not displaying full command text 

The Sql full text is not getting displayed in the applicaiton insights dependence section.
<EnableSqlCommandTextInstrumentation>true</EnableSqlCommandTextInstrumentation> is updated in the applicaiton insight congif file as well.
sql client package is also installed
But still that the DependencyTelemetry  is collecting data using rddf instead of 'rddp'

 "ai.internal.sdkVersion": "rddf:0.0.0-0",
 
 
