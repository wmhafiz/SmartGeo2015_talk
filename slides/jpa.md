##  JPA

- Standard Solution for Java
- Hibernate underneath

```java
@Entity
@Table(name = "JHI_ATTENDEE")
public class Attendee implements Serializable {

    @Id
    @GeneratedValue(strategy = GenerationType.AUTO)
    private Long id;

	@NotNull
    private String name;

    @Email
    @Size(max = 100)
    @Column(length = 100, unique = true)
    private String email;
}

```

note:
- annotation
- validation
