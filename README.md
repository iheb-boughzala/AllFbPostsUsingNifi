# AllFbPostsUsingNifi
Download All Posts of a Facebook Page Using Apache nifi by invoking facebook Graph api. 

Read tutorial.pdf for all steps and nifi processors configurations


Nifi WorkFlow

GetFile -> [ ExtractText -> UpdateAttribute -> InvokeHttp -> EvaluateJsonPath ] -> GetData - > ChangeFileName -> PutHDFS

