# cot-pagelist
Rendering page widgets anywhere

Изменения по сравнению с первым релизом от Trustmaster:

1. Удалил опцию вывода количества комментариев -- проще делать это по месту при помощи конструкций вида {PAGE_ROW_ID|cot_comments_count('page', $this)|cot_declension($this, 'Comments')}

2. Опционизировал поддержку user tags (в некоторых проектах это не требовалось вообще)

3. Добавил поддержку i18n (в некоторых проектах требовалось)

4. Подчистил немного

5. Добавил поддержку Star Ratings (опционально, на всякий случай)

===

Changes as compared to the initial release by Trustmaster:

1. Removed comments parts -- can be replaced using {PAGE_ROW_ID|cot_comments_count('page', $this)|cot_declension($this, 'Comments')} as needed

2. Optional user tags generation (did not need this in some projests)

3. Added i18n support

4. Minor cleanup

5. Added Star Ratings plugin support (optional)