<h2> This is patches for vmware workstation pro 15.0.x, for kernel 5.0.x. </h2>
<h3> how its work ? </h3>
<pre>
1. install vmware bundle
1. copy hostif.c.diff, userif.c.diff, vmware.15.0.kernel.5.0.sh to /tmp/
2. add permission "execute" to vmware.15.0.kernel.5.0.sh
	sudo chmod +x vmware.15.0.kernel.5.0.sh
3. execute script
	sudo bash vmware.15.0.kernel.5.0.sh
4. open vmware and install module .
5. whoooa, now vmware working.
</pre>
