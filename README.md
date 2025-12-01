# attendance-app
QR attendance
// === Class Schedule ===
// QR読み取り可能時間のルール
// ・開始15分前〜終了時間まで読み取り可能
// ・出席時間が90分以上なら100%

const classSchedule = [
  // ==== 月曜日 ====
  {
    day: "Monday",
    name: "プログラミング",
    start: "09:20",
    end:   "10:50"
  },
  {
    day: "Monday",
    name: "職業とキャリア",
    start: "11:00",
    end:   "12:30"
  },
  {
    day: "Monday",
    name: "AI開発",
    start: "13:20",
    end:   "14:50"
  },

  // ==== 火曜日 ====
  {
    day: "Tuesday",
    name: "ICT活用",
    start: "09:20",
    end:   "10:50"
  },
  {
    day: "Tuesday",
    name: "データサイエンス",
    start: "11:00",
    end:   "12:30"
  },
  {
    day: "Tuesday",
    name: "PBL",
    start: "13:20",
    end:   "14:50"
  },

  // ==== 木曜日 ====
  {
    day: "Thursday",
    name: "プログラミング",
    start: "09:20",
    end:   "10:50"
  },
  {
    day: "Thursday",
    name: "日本語",
    start: "11:00",
    end:   "12:30"
  },

  // ==== 金曜日 ====
  {
    day: "Friday",
    name: "情報",
    start: "09:20",
    end:   "10:50"
  },
  {
    day: "Friday",
    name: "経営戦略とAIビジネス",
    start: "11:00",
    end:   "12:30"
  },
];
