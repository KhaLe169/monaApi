---
id: apilichhoc
title:  API Lịch Học
---
 

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing. 

Method: Get

URL: /Api/ElearnStudentApi/GetUpcomingLessions

param: int UID ? 0, string Token ? null , int Page ? 1

Request: UID:1
 
Response:

| No. | Field           | Type     | Required | Defalut | Notes |
|-----|-----------------|----------|----------|--------:|-------|
| 1   | Code            | number   | yes      |         |       |
| 2   | Message         | string   | yes      |         |       |
| 3   | Data            | []       | yes      |         |       |
| 4   | BookingID       | number   | yes      |         |       |
| 5   | TeacherUID      | string   | yes      |         |       |
| 6   | TeacherName     | string   | yes      |         |       |
| 7   | StudentUID      | number   |          |         |       |
| 8   | StudentName     | null     |          |         |       |
| 9   | ScheduleTimeVN  | datetime |          |         |       |
| 10  | DocumentName    | null     |          |         |       |
| 11  | LessionName     | string   |          |         |       |
| 12  | LessionMaterial | string   |          |         |       |
| 13  | SkypeID         | string   |          |         |       |
| 14  | SpecialRequest  | string   |          |         |       |
| 15  | Status          | number   |          |         |       |
| 16  | FinishType      | number   |          |         |       |
| 17  | TotalResult     | number   |          |         |       |
| 18  | PageSize        | number   |          |         |       |