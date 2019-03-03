![Photo of RT](assets/images/photo.png)  

***Full name:*** RT  
***Phone:*** +7 111 111 11 11  

***Summary:***  
I would like to get more experience and knowledge in UI development.  
I have some knowledge and experience in the sphere,
such as developing simple UI parts of services, integration UI into Java's frameworks or fixing some issues into 
java scripts sources of the project.  
I decided to take part in the RSS because of my thoughts that it is a great chance to improve my knowledge.

***Skills:***
* **Java**
  * Application servers and web containers: JBoss AS, Tomcat, Jetty, WebLogic AS, IBM WS
  * Frameworks: Spring, JSP, JSF, GWT, Vaadin
  * Testing: JUnit, DBUnit
* **Methodologies:** Agile (SCRUM, Kanban, XP), RUP
* **Version Control System:** CSV, SVN, Git
* **IDE:** IntelliJ IDEA
* **Tools:** maven, sbt    

***Code example:***  
```typescript
    onReportClick(item: ValidationItem): void {
        this.reportService.getReportPath(item.phase)
            .takeUntil(this.unsubscribe)
            .subscribe(reportFilePath => {
                    try {
                        fs.accessSync(reportFilePath, fs.constants.F_OK);
                        shell.openExternal(reportFilePath);
                    } catch (err) {
                        let errorMessage = this.translate.instant("No such file or directory, access: '{{path}}'",
                            {path: reportFilePath});
                        this.alertService.error(errorMessage);
                    }
                }
            );
    }
```

***Experience:***  
I have more than ten years experience in software development. 


***Education:***  
I was graduated in 2006 by State Technical University, faculty of Information Technologies. I have passed different 
certification in different spheres, such as SCJP, SCBCD, OCP and etc.  
English level B1.

***Thank you for reading.***

