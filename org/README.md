## 按mvc划分 也称横向划分.
```
cont := new(controller.TaskController)
cont.Find()
model := new(models.StudyModels)
model.Find()
```

## 按模块划分. 也称垂直划分
```
taskCont := new(tasks.TaskController)
taskCont.Find()

taskModel := new(tasks.StudyModels)
taskModel.Find()
```