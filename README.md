# Task Management System
Its a simple web api project to provide a understanding of the clean architechture with Ef Core and Unit of work pattern

### Table Details
###### Task
  * Id - Guid
  * Title - string
  * Description - string
  * CreatedDate - datetime
  * CreatedBy - guid
  * LastUpdatedBy - guid
  * LastUpdatedDate - datetime
  * DueDate - datetime  
  * Status - string
  * ProjectId - guid - FK of Project
###### User
  * Id - Guid
  * Name - string
  * Mobile - string
  * Email - string
  * CreatedBy - guid
  * CreatedDate - datetime
  *  LastUpdatedBy - guid
  * LastUpdatedDate - datetime
  * IsActive - bool
##### TaskAssigned
  * Id - Guid
  * TaskId - guid
  * UserId - guid
  * CreatedDate - datetime
  * CreatedBy - guid
  * LastUpdatedBy - guid
  * LastUpdatedDate - datetime
###### Comments
  * Id - Guid
  * TaskId - Guid
  * UserId - Guid
  * Comment - string
  * IsActive - bool
  * CreatedDate - datetime
  * CreatedBy - guid
  * LastUpdatedBy - guid
  * LastUpdatedDate - datetime
###### Project
  * Id - Guid
  * Name - string
  * Description - string
  * ProjectOwner - guid
  * CreatedBy - guid
  * CreatedDate - datetime
  * LastUpdatedBy - guid
  * LastUpdatedDate - datetime
    


