+++
author = "សយ ទិត"
title = "ប្រព័ន្ធគ្រប់គ្រងព័ត៌មានសិស្ស (MIS) ដោយប្រើប្រាស់ Java, IntelliJ, និង LGoodDatePicker"
date = "2024-03-24"
description = "ការណែនាំលម្អិតអំពីការបង្កើតប្រព័ន្ធគ្រប់គ្រងព័ត៌មានសិស្ស (MIS) ដោយប្រើប្រាស់ Java ជាមួយ IntelliJ IDE។ គម្រោងនេះបង្ហាញពីវិធីគ្រប់គ្រងទិន្នន័យសិស្សដោយប្រើ MySQL ដែលផ្តោតលើសកម្មភាព CRUD និងការអភិវឌ្ឍន៍ GUI ដោយប្រើ Java Swing។"
tags = [
    "ការងារសាលា",
]
categories = [
    "ការងារសាលា",
]
series = ["Themes Guide"]
aliases = ["migrate-from-jekyll"]
image = "https://github.com/user-attachments/assets/57aac562-8651-4e5d-9914-e93bec96e82d"
+++


<div align="center">

# 🏅ប្រព័ន្ធគ្រប់គ្រងព័ត៌មានសិស្ស🏅
<img alt="GitHub License" src="https://img.shields.io/github/license/ikhode-arena/MIS-Java-Intellij">
<img alt="GitHub forks" src="https://img.shields.io/github/forks/ikhode-arena/MIS-Java-Intellij">
<img alt="GitHub Release" src="https://img.shields.io/github/v/release/ikhode-arena/mis-java-intellij">
<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/ikhode-arena/MIS-Java-Intellij">

</div>

## 🎯 **អារម្ភកថា**

គម្រោងនេះផ្តោតលើការបង្កើតប្រព័ន្ធគ្រប់គ្រងព័ត៌មានសិស្ស (MIS) ដោយប្រើប្រាស់ Java ជាមួយ IDE IntelliJ។ ប្រព័ន្ធនេះប្រើមូលដ្ឋានទិន្នន័យ MySQL ដើម្បីដំណើរការការប្រតិបត្តិ CRUD (បង្កើត, អាន, បច្ចុប្បន្នភាព, លុប) សម្រាប់គ្រប់គ្រងទិន្នន័យសិស្ស។ វាក៏មានមុខងារប្រើប្រាស់ GUI ដែលងាយស្រួលសម្រាប់អ្នកប្រើ ដែលត្រូវបានអភិវឌ្ឍដោយប្រើ Java Swing។

### **លក្ខណៈពិសេសរបស់ប្រព័ន្ធគ្រប់គ្រង**

- **Java Swing GUI**: មុខងារប្រព័ន្ធប្រើប្រាស់ក្រាហ្វិក (GUI) ត្រូវបានរចនាដោយប្រើ Java Swing ក្នុង IntelliJ។
- **ការរួមបញ្ចូល MySQL**: តភ្ជាប់ទៅមូលដ្ឋានទិន្នន័យ MySQL ដើម្បីដំណើរការទិន្នន័យសិស្ស។
- **ការរួមបញ្ចូល LGoodDatePicker**: អនុវត្ត LGoodDatePicker ដើម្បីបង្កើនប្រសិទ្ធភាពក្នុងការជ្រើសរើសកាលបរិច្ឆេទនៅក្នុង GUI។
- **ប្រតិបត្តិ CRUD**: អនុញ្ញាតឱ្យអ្នកប្រើធ្វើការប្រតិបត្តិ CRUD (បង្កើត, អាន, បច្ចុប្បន្នភាព, លុប) លើកំណត់ត្រាសិស្ស។
- **ការដោះស្រាយកំហុស**: អនុវត្តការដោះស្រាយកំហុសដោយប្រើ try-catch blocks ដើម្បីធានាបាននូវការដំណើរការយ៉ាងរលូន។

## 💪 **សៀវភៅណែនាំក្នុងការដំឡើង**

អនុវត្តការរក្សារដូចខាងក្រោមដើម្បីដំឡើង និងដំណើរការគម្រោងនេះ៖

1. **ទាញយក MySQL Connector/J**:
   - ធានាថាអ្នកមានបណ្ណាល័យ MySQL Connector/J សម្រាប់ Java។
2. **ទាញយក LGoodDatePicker**:
   - រួមបញ្ចូលបណ្ណាល័យ LGoodDatePicker នៅក្នុងការគ្រប់គ្រងការពាក់ព័ន្ធគម្រោងរបស់អ្នកសម្រាប់ការដោះស្រាយកាលបរិច្ឆេទកម្រិតខ្ពស់។

3. **នាំចូលទៅក្នុង IntelliJ**:
   - នាំចូលគម្រោងទៅក្នុង IntelliJ ដោយកំណត់រចនាសម្ព័ន្ធគម្រោង និងបន្ថែមការពាក់ព័ន្ធដែលចាំបាច់។

4. **តម្លើងមូលដ្ឋានទិន្នន័យ MySQL**:
   - នាំចូលស្គ្រីបមូលដ្ឋានទិន្នន័យ MySQL ដែលបានផ្តល់ឱ្យទៅក្នុងម៉ាស៊ីនមូលដ្ឋានទិន្នន័យ MySQL របស់អ្នក។

5. **ដំណើរការគម្រោង**:
   - ប្រតិបត្តិគម្រោងតាមរយៈ GUI របស់ IntelliJ។

## 🏹 Script របស់ MySQL សម្រាប់ចម្លងយកទៅដាក់ក្នុង DB 

The following script creates the necessary database and tables for the Student Management Information System:

```sql
-- phpMyAdmin SQL Dump
-- version 5.2.1
-- https://www.phpmyadmin.net/
--
-- Host: 127.0.0.1
-- Generation Time: Aug 02, 2024 at 12:45 PM
-- Server version: 10.4.32-MariaDB
-- PHP Version: 8.2.12

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
START TRANSACTION;
SET time_zone = "+00:00";

-- Database: `java_activity_1`

-- Table structure for table `gender`
CREATE TABLE `gender` (
  `id` int(11) NOT NULL,
  `gender_name` varchar(50) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Insert data into `gender`
INSERT INTO `gender` (`id`, `gender_name`) VALUES
(1, 'Male'),
(2, 'Female'),
(3, 'Other');

-- Table structure for table `student`
CREATE TABLE `student` (
  `id` int(11) NOT NULL,
  `name_latin` varchar(200) NOT NULL,
  `name_khmer` varchar(200) NOT NULL,
  `gender_id` int(11) NOT NULL,
  `date_of_birth` date NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_general_ci;

-- Insert data into `student`
INSERT INTO `student` (`id`, `name_latin`, `name_khmer`, `gender_id`, `date_of_birth`) VALUES
(2, 'Jane Smith', 'ជាន ស្មិច', 2, '2001-02-20'),
(3, 'Alex Kim', 'អាលិច គីម', 3, '1999-05-30'),
(4, 'Test User', 'តេស', 1, '2024-08-08');

-- Indexes and constraints
ALTER TABLE `gender`
  ADD PRIMARY KEY (`id`);

ALTER TABLE `student`
  ADD PRIMARY KEY (`id`),
  ADD KEY `gender_id` (`gender_id`);

ALTER TABLE `gender`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=4;

ALTER TABLE `student`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=5;

ALTER TABLE `student`
  ADD CONSTRAINT `student_ibfk_1` FOREIGN KEY (`gender_id`) REFERENCES `gender` (`id`);

COMMIT;
```

## 🔯 ដេម៉ូ

![image](https://github.com/user-attachments/assets/57aac562-8651-4e5d-9914-e93bec96e82d)


### ✍️ អ្នកសរសេរ

```bibtex
@misc{java_intellij_mis,
  author = {សយ ទិត},
  title = {Student Management Information System (MIS) with Java and IntelliJ},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository}
}

```

---
### 👨‍🎓 ឯកសារពាក់ព័ន្ធ
- [Java Swing Documentation](https://docs.oracle.com/javase/tutorial/uiswing/)
- [MySQL Connector/J Documentation](https://dev.mysql.com/downloads/connector/j/)
- [IntelliJ IDEA Documentation](https://www.jetbrains.com/idea/resources/)
- [LGoodDatePicker Date Time Select Library](https://github.com/LGoodDatePicker/LGoodDatePicker)
---
