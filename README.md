課題１

ユーザを取得する際に毎回where taikaiFlag = falseをつけないといけない

この設計だとその時の状態がわからなくなる。
例えば卒業年や在学中はいつからいつまでなど


課題２
別紙参照

課題３


- ECサイト
  - 注文の取り消しを物理削除すると、たとえば、注文したときに決済が完了した場合、
取消の場合には返金する必要があるが、決済システムの都合などで即時に返金できない場合に、取り消した注文を参照することができず返金ができなくなる可能性がある。

- 学習塾進捗管理システム
  - ユーザーが再入会するというユースケースが想定されていないため、
再入会した場合は、また１からの進捗ということになり、進捗管理システムという本質的な機能と矛盾してしまう

- 物理削除の採用について
 - 実務で採用したのは過去一回だけで、商品のレビュー機能で
レビューにはタグがあり、そこで物理削除を採用した。
妥当かどうかは、「ビジネス上重要な価値を生むか」という考えに基づくと
タグは価値を生まないということになり、結果妥当だったと考えられる。