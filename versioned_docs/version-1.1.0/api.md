---
id: api
title:  API Dashboard
---
 
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.
  

Method: Get

URL: /Api/ElearnStudentApi/Dashboard

param: int UID ? 0, string token ? null

Request: UID:1
 


| No. | Field                | Type     | Required | Defalut | Notes |
|-----|----------------------|----------|----------|--------:|-------|
| 1   | Code                 | number   | yes      |         |       |
| 2   | Message              | string   | yes      |         |       |
| 3   | Data                 | []       | yes      |         |       |
| 4   | StudyProcess         | number   | yes      |         |       |
| 5   | CancelLessions       | number   | yes      |         |       |
| 6   | NumberOfLessionsLeft | number   | yes      |         |       |
| 7   | NumberOfAbsences     | number   |          |         |       |
| 8   | CompleteLessions     | number   |          |         |       |
| 9   | BookingID            | number   |          |         |       |
| 10  | TeacherUID           | number   |          |         |       |
| 11  | TeacherName          | string   |          |         |       |
| 12  | StudentUID           | number   |          |         |       |
| 13  | StudentName          | string   |          |         |       |
| 14  | ScheduleTimeVN       | datetime |          |         |       |
| 15  | DocumentName         | string   |          |         |       |
| 16  | LessionName          | string   |          |         |       |
| 17  | LessionMaterial      | string   |          |         |       |
| 18  | SkypeID              | string   |          |         |       |
| 19  | SpecialRequest       | string   |          |         |       |
| 20  | Status               | string   |          |         |       |
| 21  | FinishType           | string   |          |         |       |