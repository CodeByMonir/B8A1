# TypeScript Assignment (B8A1)

## 📌 অ্যাসাইনমেন্ট পরিচিতি

এই অ্যাসাইনমেন্টের মূল উদ্দেশ্য হলো TypeScript-এর মৌলিক ও গুরুত্বপূর্ণ বিষয়গুলো ব্যবহারিকভাবে অনুশীলন করা। এখানে TypeScript-এর type system, function, union type, type narrowing, tuple, generics, interface, class, inheritance এবং asynchronous programming-এর বিভিন্ন বিষয় নিয়ে কাজ করা হয়েছে।

এই অ্যাসাইনমেন্টের মাধ্যমে type-safe, reusable এবং maintainable code লেখার দক্ষতা অর্জনের চেষ্টা করেছি।

## 📝 Assignment Overview

এই অ্যাসাইনমেন্টে মোট আটটি programming problem সমাধান করা হয়েছে।

| Problem | Topic | Description |
|---|---|---|
| Problem 1 | Optional Parameter | Optional multiplier ব্যবহার করে দুটি সংখ্যার গুণফল নির্ণয় |
| Problem 2 | Union Type & Type Narrowing | String, number এবং boolean ইনপুটের ধরন অনুযায়ী আলাদা processing |
| Problem 3 | Readonly Tuple | Latitude, longitude ও location name ব্যবহার করে নির্দিষ্ট format-এ coordinate তৈরি |
| Problem 4 | Generics | একই ধরনের একাধিক array একত্র করে একটি array তৈরি |
| Problem 5 | Interface & Array Filtering | নির্দিষ্ট শর্ত অনুযায়ী published course নির্বাচন |
| Problem 6 | Generics & keyof | Object-এর নির্দিষ্ট property-এর value সংগ্রহ |
| Problem 7 | Class & Inheritance | Employee ও Manager class তৈরি এবং access modifiers ব্যবহার |
| Problem 8 | Promise & Async Operation | বয়স যাচাই করে Promise resolve অথবা reject করা |

## 📚 Blog Topics

অ্যাসাইনমেন্টের blog অংশে TypeScript-এর দুটি গুরুত্বপূর্ণ বিষয় নিয়ে আলোচনা করা হয়েছে।

### 1. Type vs Interface

এই blog-এ Type Alias এবং Interface-এর মধ্যে পার্থক্য, ব্যবহার, inheritance, intersection এবং declaration merging নিয়ে আলোচনা করা হয়েছে।

### 2. any vs unknown vs never

## 📚 My Blogs

1. [Type vs Interface](./B8A1/type-vs-interface.md)
2. [any vs unknown vs never](./B8A1/any-unknown-never.md)


এই blog-এ `any`, `unknown` এবং `never` type-এর ব্যবহার ও পার্থক্য ব্যাখ্যা করা হয়েছে। বিশেষভাবে `any`-এর তুলনায় `unknown` কেন বেশি type-safe, তা উদাহরণসহ তুলে ধরা হয়েছে।

## ⚠️ যেসব জায়গায় সমস্যার সম্মুখীন হয়েছি

অ্যাসাইনমেন্টটি সম্পন্ন করার সময় কয়েকটি বিষয়ে বুঝতে এবং সঠিকভাবে প্রয়োগ করতে কিছুটা সমস্যার সম্মুখীন হয়েছি।

### 1. Optional Parameter ও Default Value

`multiplier` বাদ দিলে অথবা `undefined` হলে default value কীভাবে কাজ করে, তা বুঝতে হয়েছে। বিশেষ করে `0` এবং `undefined`-এর মধ্যে পার্থক্য গুরুত্বপূর্ণ ছিল।

### 2. Union Type ও Type Narrowing

একটি function-এ `string | number | boolean` গ্রহণ করে প্রতিটি type-এর জন্য আলাদা logic প্রয়োগ করতে হয়েছে। `typeof` ব্যবহার করে type narrowing করার বিষয়টি অনুশীলন করেছি।

### 3. Output Formatting

কিছু সমস্যায় নির্দিষ্ট output format হুবহু বজায় রাখা জরুরি ছিল। বিশেষ করে string-এর শুরুতে বা শেষে অতিরিক্ত quotation mark চলে আসা এবং coordinate-এর নির্দিষ্ট format ঠিক রাখার বিষয়গুলো সংশোধন করতে হয়েছে।

### 4. Readonly Tuple ও Destructuring

Tuple-এর প্রতিটি position-এ নির্দিষ্ট type নিশ্চিত করা এবং `readonly` tuple থেকে destructuring করে value ব্যবহার করার বিষয়টি বুঝতে হয়েছে।

### 5. Generics ও keyof

Generic function তৈরি এবং `K extends keyof T` ও `T[K]` ব্যবহার করে object-এর নির্দিষ্ট property-এর value-এর type নির্ধারণ করতে বাড়তি মনোযোগ দিতে হয়েছে।

### 6. Class ও Access Modifiers

`protected` এবং `private` modifier-এর ব্যবহার, inheritance-এর মাধ্যমে parent class-এর property ব্যবহার এবং child class-এর constructor-এ `super()` কল করার বিষয়গুলো অনুশীলন করতে হয়েছে।

### 7. Promise ও Asynchronous Operation

শর্ত অনুযায়ী Promise resolve অথবা reject করা এবং নির্দিষ্ট সময় পরে resolve করার জন্য `setTimeout()` ব্যবহার করার বিষয়টি বুঝতে হয়েছে। পাশাপাশি `async` function এবং সরাসরি Promise return করার সম্পর্কও অনুশীলন করেছি।


## 🗂️ Project Structure

```text
    B8A1/
    ├── solution.ts
    ├── any-unknown-never.md
    ├── README.md
    └── type-vs-interface.md
```

## 🛠️ Technologies Used

- TypeScript
- Markdown

## 🎯 Learning Outcomes

এই অ্যাসাইনমেন্ট সম্পন্ন করার মাধ্যমে যেসব বিষয় অনুশীলন করেছি:

- Function parameter ও return type নির্ধারণ
- Optional parameter এবং default value
- Union type ও type narrowing
- Readonly tuple এবং destructuring
- Generic function ও generic constraints
- Interface এবং `keyof` operator
- Class, inheritance ও access modifiers
- Promise, resolve, reject এবং asynchronous operation
- Type-safe ও reusable code লেখার অভ্যাস

## 🏁 Conclusion

এই অ্যাসাইনমেন্টের মাধ্যমে TypeScript-এর গুরুত্বপূর্ণ ধারণাগুলো বাস্তব সমস্যার সমাধানে প্রয়োগ করার সুযোগ হয়েছে। কাজ করতে গিয়ে কিছু বিষয়ে ভুল ও বিভ্রান্তির সম্মুখীন হলেও সেগুলো শনাক্ত ও সংশোধনের মাধ্যমে TypeScript সম্পর্কে আরও পরিষ্কার ধারণা তৈরি হয়েছে।

এটি আমার TypeScript শেখার যাত্রায় একটি গুরুত্বপূর্ণ ব্যবহারিক অনুশীলন।
