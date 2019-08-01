# test-sggssai
<action name="login"  class="tutorial.Login">
 
    <interceptor-ref name="timer"/>
    <interceptor-ref name="logger"/>
    <interceptor-ref name="defaultStack"/>
 
    <result name="input">login.jsp</result>
    <result type="redirectAction">/secure/home</result>
 
</action>
