---
title: "Contact"
date: 2025-07-31T11:10:36+08:00
draft: false
language: en
description: Contact!
#featured_image: ../assets/images/featured/featured-img-placeholder.png
---
<section class="lg:pb-24">
  <div class="max-w-screen-md px-4 mx-auto">
      <p class="mb-8 font-light text-center text-gray-500 lg:mb-16 dark:text-gray-400 sm:text-xl">Leave a message.</p>
      <form action="https://formspree.io/f/mdazvdbn" method="POST" class="space-y-6">
        <div>
          <label for="name" class="block text-sm font-medium text-gray-900 dark:text-gray-200 mb-2">Name</label>
          <input type="text" id="name" name="name" required class="w-full px-4 py-2 border border-gray-300 rounded-lg bg-white dark:bg-gray-800 dark:border-gray-600 dark:text-white focus:outline-none focus:ring-2 focus:ring-primary-600" required>
        </div>
        <div>
          <label for="email" class="block text-sm font-medium text-gray-900 dark:text-gray-200 mb-2">Email</label>
          <input type="email" id="email" name="email" required class="w-full px-4 py-2 border border-gray-300 rounded-lg bg-white dark:bg-gray-800 dark:border-gray-600 dark:text-white focus:outline-none focus:ring-2 focus:ring-primary-600" required>
        </div>
        <div>
          <label for="message" class="block text-sm font-medium text-gray-900 dark:text-gray-200 mb-2">Message</label>
          <textarea id="message" name="message" rows="5" required class="w-full px-4 py-2 border border-gray-300 rounded-lg bg-white dark:bg-gray-800 dark:border-gray-600 dark:text-white focus:outline-none focus:ring-2 focus:ring-primary-600" required></textarea>
        </div>
        <button type="submit" class="w-full bg-primary-600 hover:bg-primary-700 text-white font-medium py-2 px-4 rounded-lg transition duration-200">Send Message</button>
      </form>
  </div>
</section>