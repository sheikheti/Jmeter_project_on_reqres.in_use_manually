# Jmeter_project_on_reqres.in_use_manually

Dear, 

I've completed performance test on reqres.in website, tested API are:  register, create, list resource,update and delete.

Test executed for the below mentioned scenario in url https://reqres.in/

20 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 1.667 And Total Concurrent API requested: 100.
400 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 33.333 And Total Concurrent API requested: 2000.
700 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 58.333 And Total Concurrent API requested: 3500.
1000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 83.333 And Total Concurrent API requested: 5000.
1300 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 108.333 And Total Concurrent API requested: 6500.
1700 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 140 And Total Concurrent API requested: 8500.


While executed 1700 concurrent request, found  96 request got connection timeout and error rate is 1.13%. 

Summary: Server can handle almost concurrent 6000 API call with almost zero (0) error rate.

Please find the details report from the attachment and  let me know if you have any further queries
