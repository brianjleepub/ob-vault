# Main Map of Content (_home.md)

# Azure AI Learning Hub 🚀

## 🗺️ Navigation
- [[azure-learning-moc|Azure Learning Map]]
- [[projects-moc|Projects Overview]]
- [[resources-moc|Learning Resources]]
## 🎯 Quick Links
- [[course-progress|Course Progress]]
- [[current-project|Current Project]]
- [[daily-tasks|Today's Tasks]]
- [[troubleshooting|Troubleshooting Guide]]
- [[glossary|Terms & Concepts]]

## 📊 Progress Dashboard

```dataview
TABLE 
  topic as "Topic",
  progress as "Progress",
  time-spent as "Time Spent"
FROM "10-CourseWork"
WHERE type = "module"
SORT progress DESC
```
## 🚧 Active Projects
```dataview
TABLE 
  status as "Status",
  start-date as "Started"
FROM "20-Projects/in-progress"
WHERE type = "project"
SORT start-date DESC
```

## 📝 Recent Notes
```dataview
TABLE 
  file.mtime as "Last Modified"
FROM "30-Daily"
SORT file.mtime DESC
LIMIT 5
```


## 🔍 Quick Reference

- [[azure-commands|Common Azure Commands]]
- [[kubernetes-cheatsheet|Kubernetes Cheatsheet]]
- [[openai-integration|OpenAI Integration Guide]]

## 🎓 Learning Milestones

- [ ]  Azure Fundamentals
- [ ]  Kubernetes Basics
- [ ]  OpenAI Implementation
- [ ]  First Project Completion

