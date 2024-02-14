<template>

    <h1> Dismissablealerts</h1>
    <div class="alert-wrapper">
      <div class="primary-alert-box">
       <strong>This is a primary alert ! Please check it out</strong>     <span>x</span>
    </div>
      <div class="secondary-alert-box">
       <strong> This is a secondary alert ! Please check it out</strong><span>x</span>
      </div>
      <div class="success-alert-box">
       <strong>This is a success alert ! Please check it out</strong> <span> x</span>
      </div>
      <div class="danger-alert-box">
        This is a danger alert ! Please check it out<span>x</span>
      </div>
      <div class="warning-alert-box">
        This is a warning alert ! Please check it out<span>x</span>
      </div>
      <div class="info-alert-box">This is a info alert ! Please check it out <span>x</span></div>
     

      <div class="dark-alert-box">This is a dark alert ! Please check it out <span>x</span></div>
     
    </div>
  </template>
  
  <style scoped>
  .primary-alert-box {
    color: #7367f0;
    background-color: #e9e7fd;
    border-color: #e9e7fd;
    border-radius: "6px";
    display: inline-block;
    padding: 11px;
    width: auto;
   
   
  }

  .primary-alert-box span{ 
   
   margin-left: 20px;
   border-radius: "6px";
  }
  .secondary-alert-box {
    color: #a8aaae;
    background-color: #f1f1f2;
    border-color: #f1f1f2;
    border-radius: 6px;
    position: relative;
    padding: 11px;
    display: inline-block;
    width: auto;
  }


  .secondary-alert-box span{


    margin-left: 20px;


  }
  .success-alert-box {
    color: #28c76f;
    background-color: #ddf6e8;
    border-color: #ddf6e8;
    border-radius: 6px;
    position: relative;
    padding: 11px;
    display: inline-block;
    width: auto;
  }
  
  .success-alert-box span{
    color: #28c76f;
margin-left: 20px;


}
  .warning-alert-box {
    color: #ff9f43;
    background-color: #fff0e1;
    border-color: #fff0e1;
    border-radius: 6px;
    position: relative;
    padding: 11px;
    display: inline-block;
    width: auto;
  }

  .warning-alert-box span{

    color: #ff9f43;

margin-left: 20px;


}
  
  
  .danger-alert-box {
    color: #ea5455;
    background-color: #fff0e1;
    border-color: #fff0e1;
    border-radius: 6px;
    position: relative;
    padding: 11px;
    display: inline-block;
    width: auto;
  }

  .danger-alert-box span{

margin-left: 20px;


}
  
  .info-alert-box {
    color: #00cfe8;
    background-color: #d6f7fb;
    border-color: #d6f7fb;
    border-radius: 6px;
    position: relative;
    padding: 11px;
    display: inline-block;
    width: auto;
  }

  .info-alert-box span{

margin-left: 20px;


}
  
  .dark-alert-box {
    color: #4b4b4b;
    background-color: #e2e2e2;
    border-color: #e2e2e2;
  
    border-radius: 6px;
    position: relative;
    padding: 11px;
    display: inline-block;
    width: auto;
  }

  .dark-alert-box span{
    color: #4b4b4b;

margin-left: 20px;


}
  </style>