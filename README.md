# hb-01-one-to-one-uni

Class Instructor {
...
@OneToOne(cascade = CascadeType.ALL)
@JoinColumn(name="instructor_detail_id") 
private InstructorDetail instructorDetail;
...
}
