# Create a vtep VDS {#task_iyb_qc1_hgb .task}

This topic describes how to create a vtep vSphere Distributed Switch \(VDS\).

1.  You have logged on to the Windows instance on which vCenter Server is installed.
2.  You have logged on to **vSphere Web Client**.

1.   In the left-side navigation pane, click **vmc-xdragon**, and then choose **Actions** \> **Distributed Switch** \> **New Distributed Switch**.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/84968/154886340135566_en-US.png)

 
2.   In the **Name** text box, enter a name for the new VDS. In this example, vtep-vds is used.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/84968/154886340135567_en-US.png)

 
3.   On the Select version page, select **Distributed switch: 6.5.0**, and then click **Next**.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/84968/154886340135569_en-US.png)

 
4.   Select the **Number of uplinks** and select the **Default port group**. 

    **Note:** Uplink ports connect the distributed switch to physical NICs on associated hosts. The number of uplink ports is equal to the maximum number of allowed physical connections to the distributed switch of each host.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/84968/154886340135570_en-US.png)

5.  Enter a name for the port group, and then click **Next**. 
6.   On the Ready to complete page, confirm your settings, and then click **Finish**.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/84968/154886340135571_en-US.png)

 
