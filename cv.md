1. Имя, фамилия (реальные)
2. Контакты (желательно несколько)
3. Summary (цель, пожелания, раскрыть, что важно, что хочется и почему. 
Некий вариант самопрезентации. Когда опыта минимум, джун продает свой потенциал, 
свое желание и способность быстро учиться. Не занимать позицию, что он придет, 
и все кинутся его учить. Но обратное – у джуна время все брать, отовсюду, всегда и т.д.).
4. Skills (например: языки программирования, фреймворки, методологии, системы контроля версий, тулы...)
5. Примеры кода (по возможности СВЕЖИЕ)
6. Опыт (Junior-у имеет смысл указать весь опыт: тестовые задания, проекты с курсов,
фрилансовые проекты – все, где он применял вышеупомянутые скилы. 
Круто, если это будет со ссылками на код)
7. Образование (в т.ч. курсы, семинары, лекции, онлайн-обучение)
8. Уровень английского (тут стоит указать, какая именно практика была, как долго и т.д.) 

![Photo of RT](./asserts/images/photo.png)

Full name: RT  
Phone: +7 111 111 11 11  

Summary:  

Skills:
* Java
  * Application servers and web containers: JBoss AS, Tomcat, Jetty, WebLogic AS, IBM WS
  * Frameworks: Spring, JSP, JSF, GWT, Vaadin
  * Testing: JUnit, DBUnit
* Methodologies: Agile (SCRUM, Kanban, XP), RUP
* Version Control System: CSV, SVN, Git
* IDE: IntelliJ IDEA
* Tools: maven, sbt    

Code example:  
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

Experience:  
I have more than ten years experience in software development. 


Education:  
I was graduated in 2006 by State Technical University, faculty of Information Technologies. I have passed different 
certification in different spheres, such as SCJP, SCBCD, OCP and etc.  
English level B1.

