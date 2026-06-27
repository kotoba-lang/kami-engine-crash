# crash-clj

Reduced-order frontal-crash solver (`:rom-crash`) — energy-balance crush model → deceleration + rail-stress safety factor. Replaces the closed-form structural SF proxy in vehicle-design-actor/simverify. A kami-cae explicit FEA registers `:explicit-fea` on the same contract.

Part of the clean-sheet vehicle-design / CAE stack (purpose-split shared libs).
Zero-dep portable `.cljc`. Run `clojure -M:test`.
