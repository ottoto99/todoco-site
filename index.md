<script>
document.addEventListener('DOMContentLoaded', function () {
  var lang = (navigator.language || navigator.userLanguage || 'en').toLowerCase();
  var target = lang === 'ja' || lang.indexOf('ja-') === 0 ? 'ja' : 'en';
  if (target !== 'en') {
    var enEl = document.getElementById('lang-en');
    if (enEl) enEl.style.display = 'none';
    var targetEl = document.getElementById('lang-' + target);
    if (targetEl) targetEl.style.display = '';
  }
});
</script>

<div id="lang-en">
<h1>Todoco — Todo List for Everyday Planning</h1>
<p>A list-first task manager for today, inbox, projects, and upcoming tasks.</p>
<h2>Features</h2>
<ul>
<li><strong>Task Flow Management</strong> — Manage your day with Today, Inbox, Projects, and Upcoming views. Review overdue, due today, and future tasks in one place.</li>
<li><strong>Project-Based Lists</strong> — Keep every task in a project. Tasks without a specified project are added to Inbox.</li>
<li><strong>Detailed Task Records</strong> — Add titles, subtitles, notes, due dates, reminders, recurring schedules, subtasks, comments, and attachments.</li>
<li><strong>Subtasks and History</strong> — Track one-level subtasks and keep completed task history available for review.</li>
<li><strong>Search and Export</strong> — Search across tasks, projects, comments, subtasks, and attachment names. Export task data as CSV when needed.</li>
<li><strong>Compatible with</strong> daily task management, personal projects, work checklists, household planning, and recurring routines.</li>
</ul>
<hr>
<p><a href="./privacy">Privacy Policy</a> · <a href="./support">Support</a> · <a href="./terms">Terms of Use</a></p>
<p>Developer: ottoto · Contact: clientcenter99@gmail.com</p>
</div>

<div id="lang-ja" style="display:none">
<h1>Todoco — Todoリスト</h1>
<p>今日、インボックス、プロジェクト、近日予定をリスト中心で整理するタスク管理アプリ。</p>
<h2>主な機能</h2>
<ul>
<li><strong>タスクフロー管理</strong> — 今日、インボックス、プロジェクト、近日予定を切り替えながら、期限切れ、今日、未来のタスクを一つの流れで管理できます。</li>
<li><strong>プロジェクト別リスト</strong> — すべてのタスクをプロジェクトに整理できます。プロジェクト指定がないタスクはインボックスに追加されます。</li>
<li><strong>詳細なタスク記録</strong> — タイトル、サブタイトル、メモ、期日、リマインダー、繰り返し、サブタスク、コメント、添付ファイルをまとめて管理できます。</li>
<li><strong>サブタスクと履歴</strong> — 1階層のサブタスクを管理し、完了済みタスクの履歴も確認できます。</li>
<li><strong>検索と書き出し</strong> — タスク、プロジェクト、コメント、サブタスク、添付ファイル名を横断検索できます。必要に応じてCSV書き出しも可能です。</li>
<li><strong>対応用途</strong> — 日々のタスク管理、個人プロジェクト、仕事のチェックリスト、家事、繰り返しルーティンなどに最適です。</li>
</ul>
<hr>
<p><a href="./privacy">プライバシーポリシー</a> · <a href="./support">サポート</a> · <a href="./terms">利用規約</a></p>
<p>運営者: ottoto · 連絡先: clientcenter99@gmail.com</p>
</div>
