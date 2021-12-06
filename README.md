``` js
    let developer = {
    name: "Kaique",
    age: 23,
    perspective: "Back End",
    language: "JavaScript",
    framework: "NodeJs",
    searchJob: true,

    presentation() {
        return console.log(`Hi, I'm ${this.name}, I'm ${this.age} years old, I'm currently studying ${this.perspective} development with ${this.language} and ${this.framework}`);
    },

    newJob(searchJob) {
        if (searchJob) {
            return console.log("I'm looking for new experiences");
        } else {
            return console.log("I'm fine with my current position");
        }
    }

};
```
My personal [Web Site](http://matdev.online/)
