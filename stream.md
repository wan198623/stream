# stream
####数据流，三种数据流：
#####读的数据流 readStream
1.fs.createReadStream(path,[opts]);

1.1事件

     事件名说明

     data：当数据读取的时候

     close：当数据读完的时候

1.2方法

    pause()：读取数据暂停

    resume():继续读取数据

    pipe():通道 由读取流安全的传输到下一个流

#####写的数据流 writeStream

   fs.createWriterStream(path,[opts])

#####双向数据流 stream.Duplex

####_trabsform