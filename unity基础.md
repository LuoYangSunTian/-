# unity基础

* **==unity程序执行顺序==**
* Awake

* OnEnable  **只要脚本被启用就会执行**

* Start

* FixedUpdate   **针对物理运动**

* OnTriggerEnter   **触发器**

* OnCollisionEnter   **碰撞体**

* OnMouseup  **鼠标抬起**   <u>不能再iphone上实现</u>

* OnMouseDown  **鼠标按下**    <u>移动设备屏幕触摸</u>

* Update

* LateUpdate

* OnGUI   **屏幕上渲染画面**

* OnDestroy

---

==unity函数==

* Awake();无论script是否启动，都在开始时候执行
* Start();代码运行的一开始时候执行
* Update（）；每一帧执行，单次点击的函数放在其中执行，与*Time.Fixeddeltime配合使用优化效果
* FixedUpdate（）；例如移动等连续执行的函数放在其中与*Time.deltime配合使用优化效果
* transform.DetachChildren();断绝父级对象与子级的父子关系
* Destroy（）；销毁对象
* Transform 变量名；引用其他对象的位置给变量
* 刚体名.velocity=new Vector2();使物体发生移动
* OnTriggerEnter2D(Collider2D collision)；判断是否有对象进入触发器范围
* [Collider2D](https://docs.unity3d.com/cn/2020.2/ScriptReference/Collider2D.html).OnTriggerExit2D(Collider2D)；判断是否离开触发器范围
* OnCollisionEnter2D(Collision2D collision)；判断是否有对象进入碰撞器范围
* 

，