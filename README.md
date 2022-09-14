# DialogFlow

(1) Under `summaries-hotel` folder is over 2k of summaries of dialogs from MultiWOZ 2.4 that is hotel-related

(2) Under `summaries-hotel-booked` is the subset of (1) where the booking was completed during the dialog (about 1.3k dialogs)

(3) Under `summaries-hotel-only` is the subset of (2) where there is no discussion of other types of service during the conversation (so hotel booking only). (230 dialogs)

(4) Under `summaries-hotel-only-all` is all dialogs from MultiWOZ 2.4 that satisfies the same criterion as (3), i.e. hotel-only and completion of booking. (432 dialogs)

(5) Under `summaries-hotel-only-all2` is same dialogs as (4) but summaries generated with a different prompt (that seems to make InstructGPT less likely to make up steps that dont exist in dialogs)

See slides https://docs.google.com/presentation/d/1fSVIjLmEJyzBSvE9dNkO4d9uR7AMEcVHv8QR_usl9Tw/edit?usp=sharing for examples of (3)
