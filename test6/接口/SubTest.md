<!-- markdownlint-disable MD033-->
<!-- 禁止MD033类型的警告 https://www.npmjs.com/package/markdownlint -->

# 接口：publishTest  [返回](../README.md)
用例： [发布实验](../用例/发布实验.md)

- 功能：
    教师发布新的实验任务。
    
- 权限：
    老师  
    
- API请求地址： 
    接口基本地址/v1/api/publishTest

- 请求方式 ：
    POST

- 请求实例：

        {
            "course_id":1,
            "title":"实验1",
            "desc":"通过本实验完成以下要求:
            1.xxxx
            2.xxxx
            3.xxxx
        }
        
- 请求参数说明:        

  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |course_id|实验所属课程的编号|
  |title|实验的标题| 
  |desc|实验的描述|
  |link|实验的详细介绍地址（github地址）|
  
- 返回实例：

        {         
            "status": true,
            "info": null,    

        }
 
- 返回参数说明： 
 
  |参数名称|说明|
  |:---------:|:--------------------------------------------------------|      
  |status|bool类型，true表示正确的返回，false表示有错误|
  |info|返回结果说明信息|


