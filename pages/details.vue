<template>
  <div class="flex flex-col items-center justify-center min-h-screen my-24 text-center">
    <h1 class="block text-3xl title md:text-5xl xl:text-6xl">Details</h1>
    <div class="w-4/5 md:w-1/2 mx-auto my-10 text-left">
      <h4 class="block text-lg font-bold title md:text-xl">Motivation</h4>
      <p class="my-2">
        Designed for high school students, Quantum Computing Initiative (QCI) is a 3-week introduction to quantum computing. Unlike other programs, QCI integrates both conceptual and hands-on learning, allowing students to deeply engage with the subject. QCI covers the intuition, physics, mathematics, and programming knowledge necessary for quantum computing in a way that is challenging yet accessible. Classes are free and run online!
      </p>
      <h4 class="block mt-5 text-lg font-bold title md:text-xl">What is Quantum Computing?</h4>
      <p class="my-2">
        Quantum computing is an emerging field at the intersection of mathematics, computer science, and physics. Thanks to the world of quantum mechanics, these computers can tackle problems that no classical computer could ever solve; thus, they will prove to be invaluable to research in areas ranging from medicine to climate science to computer security.
      </p>
      <h4 class="block mt-5 text-lg font-bold title md:text-xl">Prerequisites (recommended)</h4>
      <p class="my-2">
        As QCI classes will be relatively in-depth, students are strongly encouraged to have a foundation in algebra, trigonometry, and basic chemistry or physics. A basic understanding of Python or another high-level programming language is also recommended. Those without these prerequisites are still welcome to join, although the pace of this class might be a bit fast.
      </p>
      <h4 class="block mt-5 text-lg font-bold title md:text-xl">About Me</h4>
      <p class="mt-2">
        I’m <a class="font-semibold hover:opacity-75" href="https://tanaybiradar.com" target="_blank">Tanay Biradar</a>, a high school senior from California who is passionate about software development and writing code for quantum computers. I often spend my free time writing software, playing soccer, learning Mandarin, or speedsolving the Rubik’s Cube.
      </p>
    </div>
    <a class="px-8 py-2 mx-2 text-indigo-800 border-2 border-indigo-500 rounded hover:bg-indigo-100" href="https://forms.gle/cSNSKn4v5odrHpRz9" target="_blank">Register</a>
    <div class="my-5 text-left w-4/5 md:w-auto">
      <ul>
        <li>3 weeks, 9 classes</li>
        <li>Mondays, Wednesdays, Fridays 5:00pm-6:30pm PST (GMT-7:00)</li>
        <li>Session 1: May 31, 2021 - June 18, 2021</li>
        <li>Free, online</li>
        <li>Grades 9-12+</li>
      </ul>
      <table class="my-10 table-fixed">
        <thead>
          <tr>
            <th>Date</th>
            <th class="text-right">Topic</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="pr-8">5/31</td>
            <td class="text-right">The classical computing paradigm</td>
          </tr>
          <tr>
            <td class="pr-8">6/2</td>
            <td class="text-right">Intro to linear algebra and programming with Qiskit</td>
          </tr>
          <tr>
            <td class="pr-8">6/4</td>
            <td class="text-right">Intro to quantum mechanics and quantum computing</td>
          </tr>
          <tr>
            <td class="pr-8">6/7</td>
            <td class="text-right">Quantum Gates [0]: Addition from scratch on a quantum computer</td>
          </tr>
          <tr>
            <td class="pr-8">6/9</td>
            <td class="text-right">Quantum Gates [1]: State vectors, superposition, and entanglement</td>
          </tr>
          <tr>
            <td class="pr-8">6/11</td>
            <td class="text-right">Project: Generating truly random numbers</td>
          </tr>
          <tr>
            <td class="pr-8">6/14</td>
            <td class="text-right">Surpassing classical computers [0]: The Deutsch Oracle</td>
          </tr>
          <tr>
            <td class="pr-8">6/16</td>
            <td class="text-right">Surpassing classical computers [1]: Grover’s Algorithm</td>
          </tr>
          <tr>
            <td class="pr-8">6/18</td>
            <td class="text-right">The past, present, and future of quantum computing</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="flex justify-between pt-10">
      <nuxt-link class="px-8 py-2 mx-2 text-gray-800 border-2 border-gray-500 rounded hover:bg-gray-100" to="/">Home</nuxt-link>
    </div>
  </div>
</template>
