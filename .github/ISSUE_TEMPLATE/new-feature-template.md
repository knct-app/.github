---
name: New Feature Template
about: The issue template for new features
title: FEATURE [CODE]
labels: new feature
assignees: ''

---

Feature Name: xyz
Feature Description: xyz

---

### Steps:
1. Do this
2. Do that
3. And finally do this

---

### API End Point:
```javascript
http://localhost:3002/{route_name}
HTTP Verb: {verb_name} //PUT POST GET ...etc
Protected: {Yes/No}
```
### Front-end Request:
```javascript
const body={...}
```
### Back-end Response:
- Success
```javascript
{msg:'Success Msg'}
```
- Error 
1. Generic Error
```javascript
{msg:'Error Msg'}
```
2. DB Error
```javascript
{msg:'DB Error'}
```
### Note:
@tag_yourself
1. Point x
2. Point y

# Reminder

- [ ] I, @tag_yourself, have added the correct projects / milestones / labels / assignees to this issue
