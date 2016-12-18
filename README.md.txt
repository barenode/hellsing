#hellsing

<pre>
  <case id="common.test" runnable="false">
    <!-- common.test:start -->
    <start id="start" target="step1" />  
    
    <!-- common.test:step1 -->
    <step id="step1" target="step2" />
    
     <!-- common.test:step2 -->
    <step id="step2" target="end" />
    
    <!-- common.test:end -->
    <end id="end" />
  </case>
  
  
  <case id="common.test2" extend="common.test">
  
    <!-- common.test:end -->
    <step id="step1" target="end" />
  </case>
</pre>


  
  
