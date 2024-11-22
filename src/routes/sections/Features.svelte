<script>
  const features = [
    {
      title: "Wi-Fi & SIM Variants",
      description: "Choose between Wi-Fi operated or SIM-based devices for flexible connectivity",
      icon: "📡"
    },
    {
      title: "Bluetooth Control",
      description: "Configure settings easily via the companion Bluetooth application",
      icon: "📱"
    },
    {
      title: "Smart Alerts",
      description: "Instant audio feedback and buzzer alerts for clear user guidance",
      icon: "🔔"
    },
    {
      title: "Cloud Integration",
      description: "Seamless cloud synchronization for attendance data",
      icon: "☁️"
    },
    {
      title: "Remote Management",
      description: "Monitor and manage devices from anywhere",
      icon: "🌐"
    },
    {
      title: "Secure Authentication",
      description: "Advanced encryption for maximum security",
      icon: "🔒"
    }
  ];
</script>

<section id="features" class="section bg-black-900">
  <div class="container">
    <div class="text-center mb-16">
      <h2 class="text-4xl font-bold text-white mb-4">Advanced Features</h2>
      <p class="text-xl text-gray-400 max-w-2xl mx-auto">Our biometric solution combines cutting-edge hardware with intelligent software for seamless authentication</p>
    </div>
    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
      {#each features as feature}
        <div class="glass-card p-6 bg-gray-800 border border-gray-700 hover:border-gray-500 transition-colors">
          <div class="text-4xl mb-4 text-white">{feature.icon}</div>
          <h3 class="text-xl font-bold text-white mb-2">{feature.title}</h3>
          <p class="text-gray-400">{feature.description}</p>
        </div>
      {/each}
    </div>
  </div>
</section>
