 ## goctl-template

 ### goctl go-zero 拓展模板




##### 生成后有些地方可能需要修改一下 , 当然是因为暂时没用把模板改完善
- 在model的  ***_gen.go  文件下  update方法 可能会需要将newDate替换成data 批量替换一下即可
- DeleteBatchById方法下 需要把第二个 fmt.Sprintf("%s%v"... 后面报错的那个字段替换成变量(id)即可
