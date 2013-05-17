To install from pypi:
 
-easy_install mock_http
+pip install mock_http
 
 Usage
 -----
@@ -26,4 +26,4 @@ mock.expects(method=GET, path='/index.html')
 resp, status = self.http.request(
     uri = 'http://localhost:%s/index.html' % self.server_port)
 assert resp['status'] == '200'
-assert mock.verify()
+assert mock.verify()