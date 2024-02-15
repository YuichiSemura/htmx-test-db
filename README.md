# Readme

My JSON Server というサービスを利用させていただきます。感謝しています。

https://my-json-server.typicode.com

## 使い方

以下のような URL で json 形式のデータを取得できます。大変便利です。

https://my-json-server.typicode.com/YuichiSemura/htmx-test-db/users

## 内容例

```json
{
  "users": [
    {
      "id": "6d487890-4d4b-42a9-92fe-b03316d90cc6",
      "name": "semura-yuichi",
      "age": 29
    },
    {
      "id": "b616c70d-ec98-47fb-8df9-873d73abb4cd",
      "name": "gotoh-hitori",
      "age": 16
    }
  ],
  "tasks": [
    {
      "id": 1,
      "priority_number": 10,
      "topic": "エリック・エヴァンスのドメイン駆動設計を読む。",
      "deadline": "2100-01-01 00:00:00.000+0900",
      "category": "reading",
      "created_timestamp": "2023-05-05 00:00:00.000+0900",
      "updated_timestamp": "2023-05-05 00:00:00.000+0900"
    },
    {
      "id": 2,
      "priority_number": 3,
      "topic": "シチューを作る",
      "deadline": "2100-01-01 00:00:00.000+0900",
      "category": "housework",
      "created_timestamp": "2024-02-14 12:03:12.406+0900",
      "updated_timestamp": "2024-02-14 12:03:12.406+0900"
    }
  ],
  "task-category": ["housework", "childcare", "programming", "reading", "self-improvement", "exercise", "other"]
}
```
