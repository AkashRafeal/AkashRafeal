public class DeveloperProfile {
    public static void main(String[] args) {
        Developer akash = new Developer();
        akash.setName("Akash Rafeal J");
        akash.setLocation("Chennai, India");
        akash.setDegree("B.Tech Information Technology");
        akash.setStack(new String[]{"Java", "Spring Boot", "Python", "MySQL", "PostgreSQL", "MongoDB"});
        akash.setCurrentlyLearning(new String[]{"Advanced Spring Boot", "Cloud Deployment"});
        akash.setFunFact("I leverage Explainable AI to figure out how vehicle rental prices change!");
        akash.motto("Building responsive web applications and scalable systems for real-world problems.");
    }
}
