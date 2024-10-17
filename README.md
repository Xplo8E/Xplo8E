`# Vinay Kumar Rasala`

[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/Xplo8E)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vinaykumarrasala)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Xplo8E)


```javascript

if (ObjC.available) {
  const SecurityResearcher = ObjC.classes.NSObject.extend({
    getProfile: function() {
      const profile = {
        name: "vinay kumar rasala",
        location: "india",
        role: "security research associate",
        expertise: [
          "iOS & Android Security",
          "mobile app pentesting",
          "reverse engineering"
        ],
        tools: ["radare2", "frida", "burpsuite"]
      };
      return ObjC.classes.NSString.stringWithString_(JSON.stringify(profile));
    },

    currentFocus: function() {
      console.log("reversing");
      console.log("ios tweak dev");
      return ObjC.classes.NSString.stringWithString_("Focusing on mobile security");
    }
  });

  ObjC.registerSubclass(SecurityResearcher, "SecurityResearcher");
  console.log("[+] SecurityResearcher class registered");
} else {
  console.log("Objective-C Runtime is not available!");
}
// Usage example:
// const researcher = ObjC.classes.SecurityResearcher.alloc().init();
// console.log(researcher.getProfile().toString());
// console.log(researcher.currentFocus().toString());
````

## Recent Blogs

- [Harnessing the Power of r2frida for Runtime Manipulation](https://www.appknox.com/blog/ios-apps-penetration-testing-r2frida-for-ios-app-runtime-manipulation)



