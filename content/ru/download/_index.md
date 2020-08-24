---
title: "Download"
linkTitle: "Download"
weight: 20
menu:
  main:
    weight: 20
---
<section class="row td-box td-box--1 position-relative td-box--gradient td-box--height-auto">
	<div class="container text-center td-arrow-down">
		<span class="h4 mb-0">
<h1><i class="fas fa-cloud-download-alt ml-2 "></i> Получить Regolith</h1>

<p>Regolith доступен как <b>отдельный ISO-образ</b>, который может быть установлен как полная операционная система Linux, и как "<b>личный архив пакетов</b>" (PPA) который устанавливает рабочий стол Regolith в существующую систему Ubuntu 18.04 или 20.04.  Эта страница обеспечивает быстрое начало установки и обновления, но  доступна <a href="../docs/getting-started/install">более подробная документация</a>.</p>
</span>
	</div>
</section>


<div class="container">
  <div class="row">
    <div class="col-sm p-5">
				<h2><i class="fas fa-compact-disc"></i> Regolith Linux ISO</h2>
				<p>
					Regolith можно установить как отдельную операционную систему, и это хороший вариант для следующих сценариев:
					<ul>
						<li>Минимальная система, небольшой размер установки, маленькое использование оперативной памяти</li>
						<li>После установки все настройки по умолчанию и пакеты находятся в заведомо исправном состоянии</li>
						<li>Обеспечивает больше брендов Regolith</li>
					</ul>
				<a href="https://github.com/regolith-linux/regolith-desktop/releases/tag/R1.4.1">Загрузите ISO-образ </a> и запишите его на USB-накопитель, чтобы установить или протестировать Regolith в качестве операционной системы. Чтобы узнать, как это сделать, посетите <a class="text-warning"  href="https://tutorials.ubuntu.com/tutorial/tutorial-install-ubuntu-desktop">руководство по установке Ubuntu</a>.</p>
				<div class="d-flex justify-content-center"><a class="btn btn-lg btn-secondary mr-3 mb-4" href="https://github.com/regolith-linux/regolith-desktop/releases/tag/R1.4.1">
      Скачать Regolith 1.4.1<i class="fas fa-cloud-download-alt ml-2 "></i></a><a class="btn btn-lg btn-primary mr-3 mb-4" href="{{< relref "/docs" >}}">
      Узнать Больше <i class="fas fa-book-reader ml-2"></i></a></div>				
			</th>
    </div>
    <div class="col-sm p-5">
			<h2><i class="fas fa-download"></i> Regolith Desktop PPA</h2>
			<p>
					Regolith можно установить в существующей системе Ubuntu 18.04 или 20.04, добавив Regolith PPA и установив пакет <code>regolith-desktop</code>.  Преимущества Regolith через PPA:
					<ul>
						<li>Больше совместимости со стандартным Ubuntu</li>
						<li>Легкое взаимодействие с другими установленными средами рабочего стола</li>
						<li>Сохранить существующую установку системы</li>
						<li>Легко удалить и вернуться в другие среды рабочего стола</li>
					</ul>
					Чтобы установить Regolith Desktop из <code>выпускаемого</code> PPA:
					<pre class="border rounded p-2">
$ sudo add-apt-repository ppa:regolith-linux/release
$ sudo apt install regolith-desktop i3xrocks-net-traffic i3xrocks-cpu-usage i3xrocks-time</pre>
					Узнайте больше о <a href="https://help.ubuntu.com/community/Repositories/CommandLine#Adding_Launchpad_PPA_Repositories">добавлении PPA здесь</a> и о PPA, <a href="../docs/getting-started/install/#ppa-sources">которые предлагает Regolith здесь</a>.
				</p>
    </div>
  </div>
</div>
