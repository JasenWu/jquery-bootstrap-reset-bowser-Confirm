浏览器默认确认功能界面重置

功能描述：
1、通过简单的调用达到重置浏览器confirm的作用；
2、简单易用;

调用示例：


 
第一个参数msg为要提示给用户看的消息；
第二个参数为用户点击确认后的回调函数；
第三个参数为用户点击取消后的回调函数；

  Jason.confirm('msg',function(){
      console.log('成功!');
  },function(){
      console.log('失败!');
  })
 
