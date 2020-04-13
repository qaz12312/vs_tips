Basics of Access Control:
  * Access control是method和component組件的集合
      *Supports(支持) confidentiality(机密性) (protects information from unauthorized disclosure)
      *Supports integrity(完整性) (protects information from unauthorized modification)
  * goal: 仅允许authorized subject(授权对象)访问object that they are permitted to access(被允许访问)
Access Control:
  * 2 parts to access control:
  * Authentication(身份验证):Who goes there?
      * Determine是否允许访问
      * Authenticate human to machine(验证人机)
      * Authenticate machine to machine(验证机器对机器)
  * Authorization(授权):被允许这样做吗？
      * Once you have access, what can you do?
      * Enforces limits on actions(限制行动)
  *  Access control usu.被當作authorization的synonym(同义词)
Access Control Basics :
  * Subject:The entity(实体) that requests access to a resource 
  * Object:The resource that a subject attempts to access
  * Least privilege philosophy:A subject is granted permissions needed to accomplish required tasks and nothing more
Controls:
  * put into place(建立)允许或禁止object access的Mechanisms(机制) 
      * 任何对unauthorized access的potential barrier(障碍)
  * Controls分为不同categories(类别)
  * Common categories:
      * Administrative(管理) (通過policies去enforce(執行) security rules)
          - Hiring practice, Usage monitoring and accounting
      * Logical/Technical (implement object access restrictions)
          - User identification and authentication, Encryption(加密)
      * Physical (限制physical access to hardware)
          - Fence(栅栏), Walls(墙壁), Locked doors(上锁的门)
Access Control Techniques:
  * 选择fit(适合)organization(组织)需求的techniques
  * Considerations include(注意事项包括)
      - 所需的安全级别
      - User和环境对security measures(安全措施)的impact
  * Techniques differ in 
      - identified objects and subjects的方式
      - 决定approve(批准)或deny(拒绝)访问
Access Control Designs:
  * def rules for users accessing files or devices
  * 3common access control designs:
      1. Mandatory(强制) access control
      2. Discretionary(自由) access control
      3. Non-discretionary(非随意) access control
Mandatory Access Control:
  * Assigns a `security label` to each subject and object
  * Matches label of subject to label of object to determine when access should be granted
  * A common implementation is `rule-based access control`
      * Often requires a subject to have `a need to know` in addition to proper security clearance
      * Need to know indicates that a subject requires access to object to complete a particular task
  * Common military data classifications
      * `Unclassified, Sensitive but Unclassified, Confidential, Secret, Top Secret`
  * Common commercial data classifications
      * `Public, Sensitive, Private, Confidential`
Discretionary Access Control:
  * Uses identity of subject to decide when to grant an access request
  * All access to an object is defined by the object owner
  * Most common design in commercial operating systems
      * Generally less secure than mandatory control
      * Generally easier to implement and more flexible
  * Includes 
      * `Identity-based access control` 
      * `Access control lists (ACLs)`
Non-discretionary Access Control:










