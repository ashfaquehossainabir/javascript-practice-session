Yesterday a interviewer asked me to do a small function like this

const a = [1,2,3] // Output [1,2,3,1,2,3]

I used spread method like this [...a,...a]

Then he asked to do it in some other way, I could have used call and apply

a.push.call(a,...a);
a.push.apply(a,a);
