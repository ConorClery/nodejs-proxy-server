# nodejs-proxy-server

The  objective  of  the  exercise  is  to  implement  a  Web  Proxy  Server.  A  Web  proxy  is  a localserver, which  fetches  items  from  the  Web  on  behalf  of  a  Web  client  instead  of  the  client  fetching  them directly. This allows for caching of pages and access control.The program should be able to:1.Respond  to  HTTP &  HTTPS requests,and  should  display  eachrequest  on  a  management console.  It  should  forward  the  request  to  the  Web  server  and  relay  the  response  to  the browser.2.Handle websocket connections.3.Dynamically blockselected URLsvia the management console.4.Efficiently cache  requestslocally  and  thus  save  bandwidth.You  must  gather  timing  and bandwidth data to prove the efficiency of your proxy.5.Handle multiple requests simultaneouslyby implementing a threaded server.The program can be written in a programming language of your choice.However, you must ensure that you do not overuse any API or Library functionality that implements the majority of the work for you.



