1	class Student{
2		private int studentID;
3		private String name;
4		private String batchName;
5		private char studentType;
6		public void setStudentID(int id){
7			studentID=id;
8		}
9		public void setName(String name){
10			this.name=name;
11		}
12		public void setBatchName(String batchName){
13			this.batchName=batchName;
14		}
15		public void setStudentType(char type){
16			studentType=type;
17		}
18		public int getStudentID(){
19			return studentID;
20		}
21		String getName(){
22			return name;
23		}
24		public String getBatchName(){
25			return batchName;
26		}
27		public char getStudentType(){
28			return studentType;
29		}
30	}
31	class Fee{
32		private Student;
33		private double fees;
34		public Student getStudent(){
35			return student;
36		}
37		public double getFees(){
38			return fees;
39		}
40		public void setStudent(Student student){
41			this.student=student;
42		}
43		public void computeFees(){
44			switch(student.getStudentType()){
45				case 'D': fees=40000;break;
46				case 'H': fees=80000;break;
47			}
48			System.out.println("Student Id:"+student.getStudentID());
49			System.out.println("Student Name:"+student.getName());
50			System.out.println("Student Batch:"+student.getBatchName());
51			System.out.println("Student Fees:"+getFees());
52		}
53	}
