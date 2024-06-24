# argo-training

argo technologies
Hii  
**purpose**
The purpose of application is to  connect source and destination by using sync policy

**Sync**
An Application is sync means, equalizing what is there in the cluster with what is there in GitHub
OutOfSync - The application details what is there in the cluster are not equal to Github
sync - The application details what is there in the cluster are equal to Github  

**all possible fields of an application yaml**
https://argo-cd.readthedocs.io/en/latest/user-guide/application-specification/

*****************************************************************************************************************************************
** **ERRORS**
1)
Failed sync attempt to 2d5aa1bd2cf03a658ad355edc1002d01b394ff53: one or more objects failed to apply, reason: ConfigMap in version "v1" cannot be handled as a ConfigMap: json: cannot unmarshal string into Go struct field ConfigMap.data of type map[string]string (retried 5 times).

**Solution**:
There is no space between : (colon) and value
Wrong    key:value1
Right:   key: value1


*****************************************************************************************************************************************
