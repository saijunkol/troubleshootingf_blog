# troubleshootingf_blog
Blog on troubleshooting

2019-5-15
Accompnay with the migration of OAuth 2.0 on spring boot, the dependency of OAuth have chenged to  
       <dependency>  
            <groupId>org.springframework.security.oauth.boot</groupId>  
            <artifactId>spring-security-oauth2-autoconfigure</artifactId>  
            <version>2.1.4.RELEASE</version>
       </dependency>  
       
2019- 5 -16 
When faced "Use of @OneToMany or @ManyToMany targeting an unmapped class:", it should be the @Entity or other annotation invoke failed.

