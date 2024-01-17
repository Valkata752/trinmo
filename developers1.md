---
title: Untitled Page
description: 
published: true
date: 2024-01-17T18:07:59.818Z
tags: 
editor: markdown
dateCreated: 2024-01-17T18:07:59.818Z
---

<main id="main">
		<div id="Walnut-Project-Area-Control-Component-View-Booking-ReservationSearch" class="page" hidden=""></div><div id="Walnut-Project-Area-Control-Component-View-Ptrans-EventSearch" class="page"><form id="ptrans-event-search" class="filter-form">
	<input id="ptrans-event-search-order_by" type="hidden" name="fetch[order_by]" value="sequence">
	<input id="ptrans-event-search-order_by_direction" type="hidden" name="fetch[order_by_direction]" value="ASC">
	<input id="ptrans-event-search-current_page" type="hidden" name="fetch[current_page]" value="1">
	<input id="ptrans-event-search-page_size" type="hidden" name="fetch[page_size]" value="50">
	<header>Събития</header>
	<section>
		<div class="filter-field">
			<label for="ptrans-event-search-message_number">№</label>
			<input id="ptrans-event-search-message_number" type="text" name="filter[message_number]">
		</div>
		<div class="filter-field">
			<label for="ptrans-event-search-name">заглавие</label>
			<input id="ptrans-event-search-name" type="text" name="filter[name]">
		</div>
		<div class="filter-field">
			<label for="ptrans-event-search-name">съдържание</label>
			<input id="ptrans-event-search-name" type="text" name="filter[description]">
		</div>
		<div class="filter-field">
			<label for="ptrans-event-search-tags">таг</label>
			<select id="ptrans-event-search-tags" name="filter[tags__tag_id]">
				<option value="">---</option>
									<option value="1">откриване на линия</option>
									<option value="2">закриване на линия</option>
									<option value="4">постоянна маршрутна промяна</option>
									<option value="7">летни разписания</option>
									<option value="8">зимни разписания</option>
									<option value="13">смяна транспортен оператор</option>
									<option value="16">реконструкция</option>
									<option value="21">задушница</option>
									<option value="22">извеждане</option>
									<option value="23">маратон</option>
									<option value="55">смяна подвижен състав</option>
									<option value="24">ВиК</option>
									<option value="25">възпоменателна</option>
									<option value="26">писменост</option>
									<option value="27">трамвайна стрелка</option>
									<option value="28">събитие</option>
									<option value="29">цветница</option>
									<option value="30">великден</option>
									<option value="31">коледа</option>
									<option value="32">нова година</option>
									<option value="33">спирка</option>
									<option value="34">гора</option>
									<option value="41">васил левски</option>
									<option value="42">армеец</option>
									<option value="12">протест</option>
									<option value="51">дондуков</option>
									<option value="52">козлодуй</option>
									<option value="53">в-к Сега</option>
									<option value="54">в-к Дневник</option>
							</select>
		</div>
		<div class="filter-field" data-field="lines">
						<details>
				<summary>линия: <span id="ptrans-event-line_id">64</span></summary>
				<label><input type="radio" name="filter[lines__line_id]" value="не" checked=""><span>всички</span></label>
									<h5>автобусни</h5>
					<ul>
													<li>
								<h6>автобуси - числово преди 1968</h6>
								<ul>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="72">
												<span>1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="73">
												<span>2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="74">
												<span>3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="75">
												<span>4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="76">
												<span>5</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="77">
												<span>6</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="78">
												<span>7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="79">
												<span>8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="80">
												<span>9</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="81">
												<span>10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="82">
												<span>11</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="83">
												<span>12</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="84">
												<span>13</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="85">
												<span>14</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="86">
												<span>15</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="87">
												<span>16</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Мърчаево">
												<input type="radio" name="filter[lines__line_id]" value="88">
												<span>17</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Редута">
												<input type="radio" name="filter[lines__line_id]" value="111">
												<span>17</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="89">
												<span>18</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="90">
												<span>19</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="91">
												<span>20</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="92">
												<span>21</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="93">
												<span>22</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="94">
												<span>23</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="95">
												<span>24</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="96">
												<span>25</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="97">
												<span>26</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="492">
												<span>26</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="493">
												<span>26</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="98">
												<span>27</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="99">
												<span>28</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="100">
												<span>29</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="101">
												<span>30</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="102">
												<span>31</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="103">
												<span>32</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="104">
												<span>33</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="105">
												<span>34</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="106">
												<span>35</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="107">
												<span>36</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="108">
												<span>37</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="109">
												<span>38</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="110">
												<span>39</span>
											</label>
										</li>
																	</ul>
							</li>
													<li>
								<h6>автобуси - числово след 1969</h6>
								<ul>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="368">
												<span>N1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="369">
												<span>N2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="370">
												<span>N3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="371">
												<span>N4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="110 -> X10">
												<input type="radio" name="filter[lines__line_id]" value="532">
												<span>X10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="530">
												<span>X50</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="109-> Х9">
												<input type="radio" name="filter[lines__line_id]" value="531">
												<span>X9</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Нощен автобус">
												<input type="radio" name="filter[lines__line_id]" value="502">
												<span>А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Нощен автобус">
												<input type="radio" name="filter[lines__line_id]" value="503">
												<span>В</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Зелена линия ВелоВитоша - Алеко">
												<input type="radio" name="filter[lines__line_id]" value="508">
												<span>ВВА</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Зелена линия ВелоВитоша - Железница">
												<input type="radio" name="filter[lines__line_id]" value="509">
												<span>ВВЖ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Допълнителна линия 1">
												<input type="radio" name="filter[lines__line_id]" value="529">
												<span>Д1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="353">
												<span>ЕЛ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="354">
												<span>ЕМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Зелена линия Витоша">
												<input type="radio" name="filter[lines__line_id]" value="488">
												<span>ЗЛВ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества метро">
												<input type="radio" name="filter[lines__line_id]" value="498">
												<span>М1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Земества метро">
												<input type="radio" name="filter[lines__line_id]" value="518">
												<span>М3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Нощен автобус">
												<input type="radio" name="filter[lines__line_id]" value="504">
												<span>С</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Ученически">
												<input type="radio" name="filter[lines__line_id]" value="519">
												<span>У1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Ученически">
												<input type="radio" name="filter[lines__line_id]" value="520">
												<span>У2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="112">
												<span>1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="113">
												<span>2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="114">
												<span>3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="гара Искър">
												<input type="radio" name="filter[lines__line_id]" value="115">
												<span>4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Горубляне">
												<input type="radio" name="filter[lines__line_id]" value="223">
												<span>4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="484">
												<span>4А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="116">
												<span>5</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="224">
												<span>5А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="117">
												<span>6</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="118">
												<span>7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="225">
												<span>7А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="119">
												<span>8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="120">
												<span>9</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="121">
												<span>10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="122">
												<span>11</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="358">
												<span>11А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="123">
												<span>12</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Подуяне">
												<input type="radio" name="filter[lines__line_id]" value="359">
												<span>13</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Младост">
												<input type="radio" name="filter[lines__line_id]" value="124">
												<span>13</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гео Милев">
												<input type="radio" name="filter[lines__line_id]" value="226">
												<span>13</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="125">
												<span>14</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Казичене">
												<input type="radio" name="filter[lines__line_id]" value="126">
												<span>15</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Кривина">
												<input type="radio" name="filter[lines__line_id]" value="227">
												<span>15</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="127">
												<span>16</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="128">
												<span>17</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="129">
												<span>18</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="394">
												<span>18А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="130">
												<span>19</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Канализация Обеля">
												<input type="radio" name="filter[lines__line_id]" value="528">
												<span>19</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="131">
												<span>20</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Закрита 16.05.2002. Разкрита отново 01.10.2020.">
												<input type="radio" name="filter[lines__line_id]" value="132">
												<span>21</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="228">
												<span>21/22</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Закрита 16.05.2002. Разкрита отново 01.10.2020">
												<input type="radio" name="filter[lines__line_id]" value="133">
												<span>22</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="134">
												<span>23</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="135">
												<span>24</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="229">
												<span>24А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="136">
												<span>25</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="357">
												<span>25А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="137">
												<span>26</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="230">
												<span>26а</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="138">
												<span>27</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Требич">
												<input type="radio" name="filter[lines__line_id]" value="139">
												<span>28</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Чепинци">
												<input type="radio" name="filter[lines__line_id]" value="231">
												<span>28</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="140">
												<span>29</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="141">
												<span>30</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="142">
												<span>31</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="143">
												<span>32</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="с. Доброславци">
												<input type="radio" name="filter[lines__line_id]" value="144">
												<span>33</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Фестивал">
												<input type="radio" name="filter[lines__line_id]" value="365">
												<span>33</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="145">
												<span>34</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Богьовци">
												<input type="radio" name="filter[lines__line_id]" value="146">
												<span>35</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Мрамор">
												<input type="radio" name="filter[lines__line_id]" value="232">
												<span>35</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="147">
												<span>36</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Опицвет">
												<input type="radio" name="filter[lines__line_id]" value="148">
												<span>37</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ботевградско шосе">
												<input type="radio" name="filter[lines__line_id]" value="233">
												<span>37</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Костинброд">
												<input type="radio" name="filter[lines__line_id]" value="149">
												<span>38</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ботевградско шосе">
												<input type="radio" name="filter[lines__line_id]" value="234">
												<span>38</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="150">
												<span>39</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="151">
												<span>40</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="152">
												<span>41</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="153">
												<span>42</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="235">
												<span>42А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="154">
												<span>43</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="236">
												<span>43А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Пожарево">
												<input type="radio" name="filter[lines__line_id]" value="155">
												<span>44</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Банкя">
												<input type="radio" name="filter[lines__line_id]" value="237">
												<span>44</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="238">
												<span>44А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="239">
												<span>44Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Златуша">
												<input type="radio" name="filter[lines__line_id]" value="156">
												<span>45</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="О.Купел">
												<input type="radio" name="filter[lines__line_id]" value="240">
												<span>45</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="157">
												<span>46</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Храбърско">
												<input type="radio" name="filter[lines__line_id]" value="158">
												<span>47</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Градоман">
												<input type="radio" name="filter[lines__line_id]" value="241">
												<span>47</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="242">
												<span>47/48</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Братушково">
												<input type="radio" name="filter[lines__line_id]" value="159">
												<span>48</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Михайлово">
												<input type="radio" name="filter[lines__line_id]" value="243">
												<span>48</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Радуловци">
												<input type="radio" name="filter[lines__line_id]" value="160">
												<span>49</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Клисура">
												<input type="radio" name="filter[lines__line_id]" value="244">
												<span>49</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="манастир Св. Петка">
												<input type="radio" name="filter[lines__line_id]" value="494">
												<span>49А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гургулят">
												<input type="radio" name="filter[lines__line_id]" value="161">
												<span>50</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Обеля">
												<input type="radio" name="filter[lines__line_id]" value="245">
												<span>50</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="162">
												<span>51</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Филиповци">
												<input type="radio" name="filter[lines__line_id]" value="163">
												<span>52</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Факултета">
												<input type="radio" name="filter[lines__line_id]" value="246">
												<span>52</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Иваняне">
												<input type="radio" name="filter[lines__line_id]" value="164">
												<span>53</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="247">
												<span>53</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Малчика">
												<input type="radio" name="filter[lines__line_id]" value="165">
												<span>54</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Мод.предградие">
												<input type="radio" name="filter[lines__line_id]" value="248">
												<span>54</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="249">
												<span>54А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Ремонт ЖП Прелез">
												<input type="radio" name="filter[lines__line_id]" value="512">
												<span>54А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Суходол">
												<input type="radio" name="filter[lines__line_id]" value="166">
												<span>55</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Божурище">
												<input type="radio" name="filter[lines__line_id]" value="250">
												<span>55</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="167">
												<span>56</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Сезонна линия">
												<input type="radio" name="filter[lines__line_id]" value="372">
												<span>56А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="168">
												<span>57</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="169">
												<span>58</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="170">
												<span>59</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="251">
												<span>59А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Горна баня">
												<input type="radio" name="filter[lines__line_id]" value="171">
												<span>60</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Рударци">
												<input type="radio" name="filter[lines__line_id]" value="252">
												<span>60</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Овча купел">
												<input type="radio" name="filter[lines__line_id]" value="253">
												<span>60</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="172">
												<span>61</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="173">
												<span>62</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="174">
												<span>63</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="254">
												<span>63А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="175">
												<span>64</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="367">
												<span>64А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="255">
												<span>64В</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Драгалевци">
												<input type="radio" name="filter[lines__line_id]" value="176">
												<span>65</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="кв. Левски">
												<input type="radio" name="filter[lines__line_id]" value="256">
												<span>65</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Ман.Ливади">
												<input type="radio" name="filter[lines__line_id]" value="257">
												<span>65</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Ремонт">
												<input type="radio" name="filter[lines__line_id]" value="521">
												<span>65A</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="177">
												<span>66</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="258">
												<span>66А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="178">
												<span>67</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="259">
												<span>67А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="179">
												<span>68</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Симеоново">
												<input type="radio" name="filter[lines__line_id]" value="524">
												<span>68</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="260">
												<span>68А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="180">
												<span>69</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Рехабилитация Околовръстен път">
												<input type="radio" name="filter[lines__line_id]" value="374">
												<span>69А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Рехабилитация Околовръстен път">
												<input type="radio" name="filter[lines__line_id]" value="375">
												<span>69Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="181">
												<span>70</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Рехабилитация Околовръстен път">
												<input type="radio" name="filter[lines__line_id]" value="377">
												<span>70А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ханчето">
												<input type="radio" name="filter[lines__line_id]" value="182">
												<span>71</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ст.Град">
												<input type="radio" name="filter[lines__line_id]" value="261">
												<span>71</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="183">
												<span>72</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Разделена линия 72">
												<input type="radio" name="filter[lines__line_id]" value="391">
												<span>72А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Разделена линия 72">
												<input type="radio" name="filter[lines__line_id]" value="392">
												<span>72Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="184">
												<span>73</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="ученическа">
												<input type="radio" name="filter[lines__line_id]" value="262">
												<span>73А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="временна линия във връзка с ремонт">
												<input type="radio" name="filter[lines__line_id]" value="410">
												<span>73А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="временна линия във връзка с ремонт">
												<input type="radio" name="filter[lines__line_id]" value="411">
												<span>73Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="185">
												<span>74</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="186">
												<span>75</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Дървеница">
												<input type="radio" name="filter[lines__line_id]" value="187">
												<span>76</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Г.Делчев">
												<input type="radio" name="filter[lines__line_id]" value="263">
												<span>76</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="188">
												<span>77</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Кремиковци">
												<input type="radio" name="filter[lines__line_id]" value="189">
												<span>78</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Левски-Г">
												<input type="radio" name="filter[lines__line_id]" value="264">
												<span>78</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="190">
												<span>79</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="395">
												<span>79А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="191">
												<span>80</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="192">
												<span>81</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="ЗТТТ">
												<input type="radio" name="filter[lines__line_id]" value="193">
												<span>82</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="265">
												<span>82</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="266">
												<span>82А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="194">
												<span>83</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="396">
												<span>83А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Автостанция Хладилника - Зоопарка">
												<input type="radio" name="filter[lines__line_id]" value="479">
												<span>83А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="195">
												<span>84</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="196">
												<span>85</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="197">
												<span>86</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="397">
												<span>86А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Септември">
												<input type="radio" name="filter[lines__line_id]" value="198">
												<span>87</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Обеля">
												<input type="radio" name="filter[lines__line_id]" value="267">
												<span>87</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Септември">
												<input type="radio" name="filter[lines__line_id]" value="199">
												<span>88</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Дружба">
												<input type="radio" name="filter[lines__line_id]" value="268">
												<span>88</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Кръстовище на две нива при бул. &quot;П. К. Яворов&quot; и ул. &quot;Ст. Михайловски&quot; ">
												<input type="radio" name="filter[lines__line_id]" value="483">
												<span>88А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="200">
												<span>89</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="201">
												<span>90</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="398">
												<span>90А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="202">
												<span>91</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="269">
												<span>91А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="203">
												<span>92</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="кв.Изток">
												<input type="radio" name="filter[lines__line_id]" value="204">
												<span>93</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Кривина">
												<input type="radio" name="filter[lines__line_id]" value="270">
												<span>93</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Драгалевци">
												<input type="radio" name="filter[lines__line_id]" value="271">
												<span>93</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="481">
												<span>93Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гео Милев">
												<input type="radio" name="filter[lines__line_id]" value="205">
												<span>94</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Казичене">
												<input type="radio" name="filter[lines__line_id]" value="272">
												<span>94</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Ст.Град">
												<input type="radio" name="filter[lines__line_id]" value="273">
												<span>94</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="206">
												<span>95</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="207">
												<span>96</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="208">
												<span>97</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="209">
												<span>98</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна линия">
												<input type="radio" name="filter[lines__line_id]" value="376">
												<span>98А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Орландовци">
												<input type="radio" name="filter[lines__line_id]" value="210">
												<span>99</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Сухата Река">
												<input type="radio" name="filter[lines__line_id]" value="356">
												<span>99</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="211">
												<span>100</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Борово">
												<input type="radio" name="filter[lines__line_id]" value="212">
												<span>101</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Славовци">
												<input type="radio" name="filter[lines__line_id]" value="274">
												<span>101</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="О.Купел">
												<input type="radio" name="filter[lines__line_id]" value="275">
												<span>101</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Ф.Жилища">
												<input type="radio" name="filter[lines__line_id]" value="276">
												<span>101</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Суходол">
												<input type="radio" name="filter[lines__line_id]" value="213">
												<span>102</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Ив.Вазов">
												<input type="radio" name="filter[lines__line_id]" value="277">
												<span>102</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ман.Ливади">
												<input type="radio" name="filter[lines__line_id]" value="278">
												<span>102А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Зах.Фабрика">
												<input type="radio" name="filter[lines__line_id]" value="214">
												<span>103</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Б.Поляни">
												<input type="radio" name="filter[lines__line_id]" value="279">
												<span>103</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="215">
												<span>104</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Връбница">
												<input type="radio" name="filter[lines__line_id]" value="216">
												<span>105</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Младост 3">
												<input type="radio" name="filter[lines__line_id]" value="280">
												<span>105</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="217">
												<span>106</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="218">
												<span>107</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="219">
												<span>108</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="399">
												<span>108А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="220">
												<span>109</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="СОП">
												<input type="radio" name="filter[lines__line_id]" value="526">
												<span>109</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="221">
												<span>110</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Абдовица">
												<input type="radio" name="filter[lines__line_id]" value="281">
												<span>110</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="СОП">
												<input type="radio" name="filter[lines__line_id]" value="527">
												<span>110</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="222">
												<span>111</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="282">
												<span>112</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Горубляне">
												<input type="radio" name="filter[lines__line_id]" value="283">
												<span>112</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="284">
												<span>113</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Дървеница">
												<input type="radio" name="filter[lines__line_id]" value="285">
												<span>114</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="МИЦ">
												<input type="radio" name="filter[lines__line_id]" value="286">
												<span>114</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="287">
												<span>115Е</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="288">
												<span>117</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="289">
												<span>118</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="290">
												<span>119</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="360">
												<span>119</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="291">
												<span>120</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="292">
												<span>121</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Асансьорен з-д">
												<input type="radio" name="filter[lines__line_id]" value="293">
												<span>122</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="лифт Симеоново">
												<input type="radio" name="filter[lines__line_id]" value="294">
												<span>122</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="295">
												<span>122А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="296">
												<span>123</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="297">
												<span>124</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="298">
												<span>125</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="299">
												<span>126</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="300">
												<span>150</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="временна линия в Обеля и Надежда">
												<input type="radio" name="filter[lines__line_id]" value="412">
												<span>150А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="301">
												<span>163</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="302">
												<span>166</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="303">
												<span>184</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="510">
												<span>185</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="304">
												<span>200</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="305">
												<span>202</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Орландовци">
												<input type="radio" name="filter[lines__line_id]" value="522">
												<span>202</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="306">
												<span>204</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="307">
												<span>209</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="гара Искър">
												<input type="radio" name="filter[lines__line_id]" value="308">
												<span>211</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Овча Купел">
												<input type="radio" name="filter[lines__line_id]" value="309">
												<span>211</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="310">
												<span>213</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="311">
												<span>214</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="312">
												<span>215</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="313">
												<span>216</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Банкя">
												<input type="radio" name="filter[lines__line_id]" value="314">
												<span>242</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="и-т Пушкаров">
												<input type="radio" name="filter[lines__line_id]" value="315">
												<span>242</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="316">
												<span>260</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="317">
												<span>261</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="318">
												<span>261А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Хладилника">
												<input type="radio" name="filter[lines__line_id]" value="319">
												<span>266</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="лифт Симеоново">
												<input type="radio" name="filter[lines__line_id]" value="320">
												<span>266</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="321">
												<span>267</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="322">
												<span>270</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="323">
												<span>276</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="324">
												<span>279</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="325">
												<span>280</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="326">
												<span>283</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="1">
												<input type="radio" name="filter[lines__line_id]" value="327">
												<span>284</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="2">
												<input type="radio" name="filter[lines__line_id]" value="328">
												<span>284</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Връбница">
												<input type="radio" name="filter[lines__line_id]" value="329">
												<span>285</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Свобода">
												<input type="radio" name="filter[lines__line_id]" value="330">
												<span>285</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="537">
												<span>288</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="1">
												<input type="radio" name="filter[lines__line_id]" value="331">
												<span>294</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="2">
												<input type="radio" name="filter[lines__line_id]" value="332">
												<span>294</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="3">
												<input type="radio" name="filter[lines__line_id]" value="333">
												<span>294</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Дружба 1">
												<input type="radio" name="filter[lines__line_id]" value="334">
												<span>304</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="бул.България">
												<input type="radio" name="filter[lines__line_id]" value="335">
												<span>304</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="336">
												<span>305</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="337">
												<span>306</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="1">
												<input type="radio" name="filter[lines__line_id]" value="338">
												<span>309</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="2">
												<input type="radio" name="filter[lines__line_id]" value="339">
												<span>309</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="340">
												<span>310</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="341">
												<span>313</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="342">
												<span>314</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="343">
												<span>361</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="344">
												<span>383</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="345">
												<span>384</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="346">
												<span>400</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="347">
												<span>404</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="348">
												<span>413</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="349">
												<span>461</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="350">
												<span>504</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="351">
												<span>505</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="352">
												<span>604</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Нощен автобус">
												<input type="radio" name="filter[lines__line_id]" value="485">
												<span>605А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Нощен автобус">
												<input type="radio" name="filter[lines__line_id]" value="486">
												<span>606В</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Нощен автобус">
												<input type="radio" name="filter[lines__line_id]" value="487">
												<span>607С</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="533">
												<span>802</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="534">
												<span>803</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="535">
												<span>804</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="536">
												<span>805</span>
											</label>
										</li>
																	</ul>
							</li>
													<li>
								<h6>автобуси - буквено</h6>
								<ul>
																			<li>
											<label data-is-active="0" title="Александровска">
												<input type="radio" name="filter[lines__line_id]" value="361">
												<span>А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Княжево">
												<input type="radio" name="filter[lines__line_id]" value="443">
												<span>А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Требич">
												<input type="radio" name="filter[lines__line_id]" value="444">
												<span>А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Суходол">
												<input type="radio" name="filter[lines__line_id]" value="464">
												<span>Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Бак.Фабрика">
												<input type="radio" name="filter[lines__line_id]" value="465">
												<span>Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Банкя">
												<input type="radio" name="filter[lines__line_id]" value="466">
												<span>Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Х.Димитър">
												<input type="radio" name="filter[lines__line_id]" value="445">
												<span>В</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Княжево">
												<input type="radio" name="filter[lines__line_id]" value="446">
												<span>В</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Връбница">
												<input type="radio" name="filter[lines__line_id]" value="460">
												<span>Г</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Божурище">
												<input type="radio" name="filter[lines__line_id]" value="461">
												<span>Г</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="473">
												<span>Д</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Сл.Река">
												<input type="radio" name="filter[lines__line_id]" value="454">
												<span>Е</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Др.Цанков">
												<input type="radio" name="filter[lines__line_id]" value="455">
												<span>Е</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="470">
												<span>Ж</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="471">
												<span>З</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Илиянци">
												<input type="radio" name="filter[lines__line_id]" value="462">
												<span>И</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Искър">
												<input type="radio" name="filter[lines__line_id]" value="463">
												<span>И</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гробища">
												<input type="radio" name="filter[lines__line_id]" value="447">
												<span>К</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Щросмайер">
												<input type="radio" name="filter[lines__line_id]" value="448">
												<span>К</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Симеоново">
												<input type="radio" name="filter[lines__line_id]" value="449">
												<span>К</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Връбница">
												<input type="radio" name="filter[lines__line_id]" value="450">
												<span>К</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Левски">
												<input type="radio" name="filter[lines__line_id]" value="468">
												<span>Л</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Лозен">
												<input type="radio" name="filter[lines__line_id]" value="469">
												<span>Л</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="474">
												<span>ЛВ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="459">
												<span>М</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="456">
												<span>Н</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="472">
												<span>О</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="475">
												<span>П</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="476">
												<span>Р</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Орлов мост">
												<input type="radio" name="filter[lines__line_id]" value="451">
												<span>С</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Симеоново">
												<input type="radio" name="filter[lines__line_id]" value="452">
												<span>С</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="453">
												<span>С-а</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Горна Баня">
												<input type="radio" name="filter[lines__line_id]" value="457">
												<span>Т</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гоце Делчев">
												<input type="radio" name="filter[lines__line_id]" value="458">
												<span>Т</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="467">
												<span>Ф</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="477">
												<span>Х</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="478">
												<span>Ч</span>
											</label>
										</li>
																	</ul>
							</li>
													<li>
								<h6>трамваи - числово</h6>
								<ul>
																			<li>
											<label data-is-active="3" title="Замества трамвай 1">
												<input type="radio" name="filter[lines__line_id]" value="388">
												<span>1ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 2">
												<input type="radio" name="filter[lines__line_id]" value="404">
												<span>2ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 3">
												<input type="radio" name="filter[lines__line_id]" value="500">
												<span>3ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 4">
												<input type="radio" name="filter[lines__line_id]" value="405">
												<span>4ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 5">
												<input type="radio" name="filter[lines__line_id]" value="366">
												<span>5ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 6">
												<input type="radio" name="filter[lines__line_id]" value="415">
												<span>6Т1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 6">
												<input type="radio" name="filter[lines__line_id]" value="416">
												<span>6Т2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 6">
												<input type="radio" name="filter[lines__line_id]" value="414">
												<span>6ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 7">
												<input type="radio" name="filter[lines__line_id]" value="378">
												<span>7ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 8">
												<input type="radio" name="filter[lines__line_id]" value="393">
												<span>8ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 9">
												<input type="radio" name="filter[lines__line_id]" value="400">
												<span>9ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 10">
												<input type="radio" name="filter[lines__line_id]" value="406">
												<span>10ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 11">
												<input type="radio" name="filter[lines__line_id]" value="407">
												<span>11ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 12">
												<input type="radio" name="filter[lines__line_id]" value="384">
												<span>12ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 14">
												<input type="radio" name="filter[lines__line_id]" value="523">
												<span>14ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 17">
												<input type="radio" name="filter[lines__line_id]" value="418">
												<span>17ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 18">
												<input type="radio" name="filter[lines__line_id]" value="389">
												<span>18ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 19">
												<input type="radio" name="filter[lines__line_id]" value="489">
												<span>19ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 20">
												<input type="radio" name="filter[lines__line_id]" value="401">
												<span>20ТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества трамвай 22">
												<input type="radio" name="filter[lines__line_id]" value="373">
												<span>22ТМ</span>
											</label>
										</li>
																	</ul>
							</li>
													<li>
								<h6>тролейбуси - числово</h6>
								<ul>
																			<li>
											<label data-is-active="3" title="Замества тролей  1">
												<input type="radio" name="filter[lines__line_id]" value="490">
												<span>1ТБ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества тролей 2">
												<input type="radio" name="filter[lines__line_id]" value="491">
												<span>2ТБ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества тролей 4">
												<input type="radio" name="filter[lines__line_id]" value="408">
												<span>4ТБ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Допълнителна">
												<input type="radio" name="filter[lines__line_id]" value="513">
												<span>5ТБ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Замества тролей 11">
												<input type="radio" name="filter[lines__line_id]" value="499">
												<span>11ТБ</span>
											</label>
										</li>
																	</ul>
							</li>
											</ul>
									<h5>тролейбусни</h5>
					<ul>
													<li>
								<h6>тролейбуси - буквено</h6>
								<ul>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="5">
												<span>И</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="4">
												<span>Л</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="2">
												<span>П</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="7">
												<span>Р</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="3">
												<span>С</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="1">
												<span>Т</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="6">
												<span>ХД</span>
											</label>
										</li>
																	</ul>
							</li>
													<li>
								<h6>тролейбуси - числово</h6>
								<ul>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="8">
												<span>1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="514">
												<span>1А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="9">
												<span>2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="385">
												<span>2А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="кв.Левски">
												<input type="radio" name="filter[lines__line_id]" value="10">
												<span>3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Сточна гара - Надлез Надежа">
												<input type="radio" name="filter[lines__line_id]" value="11">
												<span>3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="УМБАЛ Св. Анна - Надлез Надежа">
												<input type="radio" name="filter[lines__line_id]" value="517">
												<span>3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Реконструкцията на площада при паметника Васил Левски ">
												<input type="radio" name="filter[lines__line_id]" value="505">
												<span>3А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="по Ц.Шосе">
												<input type="radio" name="filter[lines__line_id]" value="12">
												<span>4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="ВМА">
												<input type="radio" name="filter[lines__line_id]" value="13">
												<span>4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Дружба">
												<input type="radio" name="filter[lines__line_id]" value="14">
												<span>4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="515">
												<span>4А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="по Ц.Шосе">
												<input type="radio" name="filter[lines__line_id]" value="15">
												<span>5</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Младост">
												<input type="radio" name="filter[lines__line_id]" value="16">
												<span>5</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="516">
												<span>5А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="17">
												<span>5Б</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Илиянци">
												<input type="radio" name="filter[lines__line_id]" value="18">
												<span>6</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="19">
												<span>6</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ремонт">
												<input type="radio" name="filter[lines__line_id]" value="20">
												<span>6А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Дойран">
												<input type="radio" name="filter[lines__line_id]" value="21">
												<span>7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="22">
												<span>7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="80-те">
												<input type="radio" name="filter[lines__line_id]" value="23">
												<span>7А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="ремонт Сливница">
												<input type="radio" name="filter[lines__line_id]" value="355">
												<span>7А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Левски">
												<input type="radio" name="filter[lines__line_id]" value="24">
												<span>8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Г.Делчев">
												<input type="radio" name="filter[lines__line_id]" value="25">
												<span>8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="386">
												<span>8А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="26">
												<span>9</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="387">
												<span>9А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="27">
												<span>10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="н-з Надежда">
												<input type="radio" name="filter[lines__line_id]" value="28">
												<span>10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="29">
												<span>11</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="506">
												<span>11А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="30">
												<span>12</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Левски">
												<input type="radio" name="filter[lines__line_id]" value="31">
												<span>12</span>
											</label>
										</li>
																	</ul>
							</li>
											</ul>
									<h5>трамвайни</h5>
					<ul>
													<li>
								<h6>трамваи - числово</h6>
								<ul>
																			<li>
											<label data-is-active="3" title="">
												<input type="radio" name="filter[lines__line_id]" value="507">
												<span>РетроТМ</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="32">
												<span>1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="383">
												<span>1А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="33">
												<span>2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна">
												<input type="radio" name="filter[lines__line_id]" value="417">
												<span>2А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="480">
												<span>2А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="34">
												<span>3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="501">
												<span>3А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ал.Стамболийски">
												<input type="radio" name="filter[lines__line_id]" value="35">
												<span>4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Бъкстон">
												<input type="radio" name="filter[lines__line_id]" value="36">
												<span>4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="37">
												<span>5</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="38">
												<span>6</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна">
												<input type="radio" name="filter[lines__line_id]" value="380">
												<span>6А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Пиротска">
												<input type="radio" name="filter[lines__line_id]" value="39">
												<span>7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Надежда">
												<input type="radio" name="filter[lines__line_id]" value="40">
												<span>7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="381">
												<span>7А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="ремонтна">
												<input type="radio" name="filter[lines__line_id]" value="413">
												<span>7А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Бояна">
												<input type="radio" name="filter[lines__line_id]" value="41">
												<span>8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="К.Величков">
												<input type="radio" name="filter[lines__line_id]" value="42">
												<span>8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Журналист">
												<input type="radio" name="filter[lines__line_id]" value="43">
												<span>8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="44">
												<span>8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна">
												<input type="radio" name="filter[lines__line_id]" value="402">
												<span>8А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Шипка">
												<input type="radio" name="filter[lines__line_id]" value="45">
												<span>9</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Хладилника">
												<input type="radio" name="filter[lines__line_id]" value="46">
												<span>9</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ал.Стамболийски">
												<input type="radio" name="filter[lines__line_id]" value="47">
												<span>10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="кв.Левски">
												<input type="radio" name="filter[lines__line_id]" value="48">
												<span>10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Зап.Парк">
												<input type="radio" name="filter[lines__line_id]" value="49">
												<span>10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна">
												<input type="radio" name="filter[lines__line_id]" value="382">
												<span>10А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Орландовци">
												<input type="radio" name="filter[lines__line_id]" value="50">
												<span>11</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Триъгълника">
												<input type="radio" name="filter[lines__line_id]" value="51">
												<span>11</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="52">
												<span>12</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна">
												<input type="radio" name="filter[lines__line_id]" value="379">
												<span>12А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="53">
												<span>13</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Орландовци">
												<input type="radio" name="filter[lines__line_id]" value="54">
												<span>14</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Хладилника">
												<input type="radio" name="filter[lines__line_id]" value="55">
												<span>14</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна линия по Дж.Баучър">
												<input type="radio" name="filter[lines__line_id]" value="409">
												<span>14А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Горнобански път">
												<input type="radio" name="filter[lines__line_id]" value="56">
												<span>15</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Зап.Парк">
												<input type="radio" name="filter[lines__line_id]" value="57">
												<span>15</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Ив.Вазов">
												<input type="radio" name="filter[lines__line_id]" value="58">
												<span>15</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Кр.Поляна">
												<input type="radio" name="filter[lines__line_id]" value="59">
												<span>15</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Лозенец">
												<input type="radio" name="filter[lines__line_id]" value="60">
												<span>16</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="СТЗ">
												<input type="radio" name="filter[lines__line_id]" value="61">
												<span>16</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="СТЗ">
												<input type="radio" name="filter[lines__line_id]" value="62">
												<span>17</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Борово">
												<input type="radio" name="filter[lines__line_id]" value="63">
												<span>17</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="СТЗ">
												<input type="radio" name="filter[lines__line_id]" value="64">
												<span>18</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="Орландовци">
												<input type="radio" name="filter[lines__line_id]" value="65">
												<span>18</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна">
												<input type="radio" name="filter[lines__line_id]" value="390">
												<span>18А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Задушница">
												<input type="radio" name="filter[lines__line_id]" value="482">
												<span>18А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="">
												<input type="radio" name="filter[lines__line_id]" value="66">
												<span>19</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="67">
												<span>20</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Люлин">
												<input type="radio" name="filter[lines__line_id]" value="68">
												<span>21</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="ст.Изток">
												<input type="radio" name="filter[lines__line_id]" value="69">
												<span>21</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="70">
												<span>22</span>
											</label>
										</li>
																			<li>
											<label data-is-active="3" title="Временна">
												<input type="radio" name="filter[lines__line_id]" value="403">
												<span>22А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="71">
												<span>23</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="525">
												<span>27</span>
											</label>
										</li>
																	</ul>
							</li>
													<li>
								<h6>трамваи - имена</h6>
								<ul>
																			<li>
											<label data-is-active="0" title="Алабинска">
												<input type="radio" name="filter[lines__line_id]" value="422">
												<span>А</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Витошка">
												<input type="radio" name="filter[lines__line_id]" value="419">
												<span>В</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гробища">
												<input type="radio" name="filter[lines__line_id]" value="424">
												<span>Г</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гарата-Игнатиев">
												<input type="radio" name="filter[lines__line_id]" value="362">
												<span>Г-И</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Княжевска">
												<input type="radio" name="filter[lines__line_id]" value="423">
												<span>К</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Пирот-Подуене">
												<input type="radio" name="filter[lines__line_id]" value="420">
												<span>ПП</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Цар Освободител">
												<input type="radio" name="filter[lines__line_id]" value="421">
												<span>ЦО</span>
											</label>
										</li>
																	</ul>
							</li>
													<li>
								<h6>трамваи - две числа</h6>
								<ul>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Гробища">
												<input type="radio" name="filter[lines__line_id]" value="363">
												<span>1-1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Военно училище-Гробища">
												<input type="radio" name="filter[lines__line_id]" value="439">
												<span>1-9</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гарата-Подуяне">
												<input type="radio" name="filter[lines__line_id]" value="433">
												<span>2-10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Гарата">
												<input type="radio" name="filter[lines__line_id]" value="425">
												<span>2-2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гарата-Арсенала">
												<input type="radio" name="filter[lines__line_id]" value="438">
												<span>2-6</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Гарата-Игрище">
												<input type="radio" name="filter[lines__line_id]" value="432">
												<span>2-7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Пирот-Подуяне">
												<input type="radio" name="filter[lines__line_id]" value="435">
												<span>3-10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Пирот">
												<input type="radio" name="filter[lines__line_id]" value="426">
												<span>3-3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Зах.Фабрика">
												<input type="radio" name="filter[lines__line_id]" value="436">
												<span>3-3а</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Пирот-Игрище">
												<input type="radio" name="filter[lines__line_id]" value="434">
												<span>3-7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Булина ливада-Подуене">
												<input type="radio" name="filter[lines__line_id]" value="441">
												<span>4-10</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Булина ливада-Орлов мост">
												<input type="radio" name="filter[lines__line_id]" value="440">
												<span>4-4</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Княжево">
												<input type="radio" name="filter[lines__line_id]" value="427">
												<span>5-5</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Арсенала">
												<input type="radio" name="filter[lines__line_id]" value="428">
												<span>6-6</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Ив.Вазов">
												<input type="radio" name="filter[lines__line_id]" value="442">
												<span>6-6а</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Игрище">
												<input type="radio" name="filter[lines__line_id]" value="429">
												<span>7-7</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Павлово-Бояна">
												<input type="radio" name="filter[lines__line_id]" value="437">
												<span>8-8</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Военно училище">
												<input type="radio" name="filter[lines__line_id]" value="430">
												<span>9-9</span>
											</label>
										</li>
																			<li>
											<label data-is-active="0" title="Св.Неделя-Подуяне">
												<input type="radio" name="filter[lines__line_id]" value="431">
												<span>10-10</span>
											</label>
										</li>
																	</ul>
							</li>
											</ul>
									<h5>метро</h5>
					<ul>
													<li>
								<h6>метро - числово</h6>
								<ul>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="364">
												<span>М1</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="495">
												<span>М2</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="496">
												<span>М3</span>
											</label>
										</li>
																			<li>
											<label data-is-active="1" title="">
												<input type="radio" name="filter[lines__line_id]" value="497">
												<span>М4</span>
											</label>
										</li>
																	</ul>
							</li>
											</ul>
							</details>
		</div>

	</section>
	<footer>
		<button>търсене</button>
		<button id="ptrans-event-search-add" class="add-button">+ събитие</button>
	</footer>
</form>
<div id="ptrans-event-search-result" class="search-result filter-result-list"><div id="ptrans-event-list-pagination" class="list-pagingation">
	Showing page	<select id="ptrans-event-list-current-page" class="list-current-page">
					<option value="1" selected="selected">1</option>
					<option value="2">2</option>
					<option value="3">3</option>
					<option value="4">4</option>
			</select>
	of	<span id="ptrans-event-list-total-pages" class="list-total-pages">4</span>.
	Show	<select id="ptrans-event-list-page-size" class="list-page-size">
					<option value="5">5</option>
					<option value="10">10</option>
					<option value="20">20</option>
					<option value="50" selected="selected">50</option>
					<option value="500">500</option>
			</select>
	entries per page.</div>
<div id="ptrans-event-list" class="list-result-list">
	<div id="ptrans-event-list-empty" class="list-result-empty" hidden="">Няма намерени събития.</div>
	<section id="ptrans-event-list-entries" class="list-entries">
		<ul class="ptrans-event-list-row list-row list-header-row">
			<li data-fill-value="message_number">#</li>
			<li data-fill-value="message_date" data-sorted="DESC">дата</li>
			<li data-fill-value="name">заглавие</li>
			<li data-fill-value="tags">тагове</li>
			<li data-fill-value="lines">линии</li>
			<li data-fill-value="attachments">схеми</li>
		</ul>
				<div class="list-data-rows">
							<ul class="ptrans-event-list-row list-row" data-entry-id="3462">
					<li data-fill-value="message_number">ЦГМ-2550</li>
					<li data-fill-value="message_date">2024-01-05</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - удължаване</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3434">
					<li data-fill-value="message_number">ЦГМ-2523</li>
					<li data-fill-value="message_date">2023-11-14</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - промяна</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/b7fa9f9f.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3383">
					<li data-fill-value="message_number">ЦГМ-2474</li>
					<li data-fill-value="message_date">2023-09-19</li>
					<li data-fill-value="name">Изместване на спирка 0912</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">73</span> <span data-mean-id="1" data-signalization-id="9" title="">83</span> <span data-mean-id="1" data-signalization-id="9" title="Дружба">88</span> <span data-mean-id="1" data-signalization-id="9" title="">120</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3370">
					<li data-fill-value="message_number">ЦГМ-2461</li>
					<li data-fill-value="message_date">2023-09-11</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - промяна</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/d458e174.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3360">
					<li data-fill-value="message_number">ЦГМ-2452</li>
					<li data-fill-value="message_date">2023-09-04</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - промяна</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/1c16bddf.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3321">
					<li data-fill-value="message_number">ЦГМ-2412</li>
					<li data-fill-value="message_date">2023-08-01</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - промяна</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3316">
					<li data-fill-value="message_number">ЦГМ-2408</li>
					<li data-fill-value="message_date">2023-07-23</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - удължаване</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3309">
					<li data-fill-value="message_number">ЦГМ-2400</li>
					<li data-fill-value="message_date">2023-07-13</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - удължаване</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3297">
					<li data-fill-value="message_number">ЦГМ-2388</li>
					<li data-fill-value="message_date">2023-07-05</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - удължаване</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3285">
					<li data-fill-value="message_number">ЦГМ-2376</li>
					<li data-fill-value="message_date">2023-06-26</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - удължаване</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3263">
					<li data-fill-value="message_number">ЦГМ-2355</li>
					<li data-fill-value="message_date">2023-06-05</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - промяна</li>
					<li data-fill-value="tags"><span>ВиК</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/4551b3ae.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3261">
					<li data-fill-value="message_number">ЦГМ-2350</li>
					<li data-fill-value="message_date">2023-05-29</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - удължаване</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3220">
					<li data-fill-value="message_number">ЦГМ-2308</li>
					<li data-fill-value="message_date">2023-04-11</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - удължаване</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3191">
					<li data-fill-value="message_number">ЦГМ-2281</li>
					<li data-fill-value="message_date">2023-03-13</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - промяна</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/15720577.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3188">
					<li data-fill-value="message_number">ЦГМ-2278</li>
					<li data-fill-value="message_date">2023-03-07</li>
					<li data-fill-value="name">Изграждане на канализация в кв. Драгалевци - начало</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="Симеоново">68</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/59a68f28.jfif" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3176">
					<li data-fill-value="message_number">ЦГМ-2267</li>
					<li data-fill-value="message_date">2023-02-18</li>
					<li data-fill-value="name">Задушница на 18.02.2023</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3141">
					<li data-fill-value="message_number">ЦГМ-2234</li>
					<li data-fill-value="message_date">2022-11-28</li>
					<li data-fill-value="name">ВиК</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">107</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/b2a17d10.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3143">
					<li data-fill-value="message_number">ЦГМ-2232</li>
					<li data-fill-value="message_date">2022-11-24</li>
					<li data-fill-value="name">ВиК</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">107</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/2670943c.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3126">
					<li data-fill-value="message_number">ЦГМ-2219</li>
					<li data-fill-value="message_date">2022-11-05</li>
					<li data-fill-value="name">Задушница на 05.11.2022</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="3" data-signalization-id="7" title="Задушница">7А</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3105">
					<li data-fill-value="message_number">ЦГМ-2188</li>
					<li data-fill-value="message_date">2022-09-24</li>
					<li data-fill-value="name">Във връзка със провеждането на Национален шампионат затворен маршрут „Писта София 2022“</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">63</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">111</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/52924a52.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3096">
					<li data-fill-value="message_number">ЦГМ-2178</li>
					<li data-fill-value="message_date">2022-09-12</li>
					<li data-fill-value="name">край на ремонт</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">107</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3079">
					<li data-fill-value="message_number">ЦГМ-2169</li>
					<li data-fill-value="message_date">2022-08-29</li>
					<li data-fill-value="name">Водопровод</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">107</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/8bd6013b.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3069">
					<li data-fill-value="message_number">ЦГМ-2156</li>
					<li data-fill-value="message_date">2022-08-13</li>
					<li data-fill-value="name">Спирки по желание</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">1</span> <span data-mean-id="1" data-signalization-id="9" title="">3</span> <span data-mean-id="1" data-signalization-id="9" title="Горубляне">4</span> <span data-mean-id="1" data-signalization-id="9" title="">23</span> <span data-mean-id="1" data-signalization-id="9" title="">26</span> <span data-mean-id="1" data-signalization-id="9" title="">27</span> <span data-mean-id="1" data-signalization-id="9" title="Чепинци">28</span> <span data-mean-id="1" data-signalization-id="9" title="">29</span> <span data-mean-id="1" data-signalization-id="9" title="">42</span> <span data-mean-id="1" data-signalization-id="9" title="">58</span> <span data-mean-id="1" data-signalization-id="9" title="">59</span> <span data-mean-id="1" data-signalization-id="9" title="">63</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">107</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="3046">
					<li data-fill-value="message_number">ЦГМ-2134</li>
					<li data-fill-value="message_date">2022-06-16</li>
					<li data-fill-value="name">Авария</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">107</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/f9d4f286.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2997">
					<li data-fill-value="message_number">ЦГМ-2079</li>
					<li data-fill-value="message_date">2022-03-21</li>
					<li data-fill-value="name">Във връзка със строително-монтажни работи</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="">66</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2984">
					<li data-fill-value="message_number">ЦГМ-2066</li>
					<li data-fill-value="message_date">2022-02-26</li>
					<li data-fill-value="name">Задушница на 26.02.2022</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Бъкстон">4</span> <span data-mean-id="3" data-signalization-id="7" title="Задушница">7А</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2750">
					<li data-fill-value="message_number">ЦГМ-2032</li>
					<li data-fill-value="message_date">2021-11-06</li>
					<li data-fill-value="name">Задушница на 06.11.2021</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Бъкстон">4</span> <span data-mean-id="3" data-signalization-id="7" title="Задушница">7А</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2672">
					<li data-fill-value="message_number">ЦГМ-1951</li>
					<li data-fill-value="message_date">2021-07-01</li>
					<li data-fill-value="name">Изместване на спирка 2313</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Ман.Ливади">65</span> <span data-mean-id="1" data-signalization-id="9" title="">83</span> <span data-mean-id="1" data-signalization-id="9" title="Дружба">88</span> <span data-mean-id="1" data-signalization-id="9" title="Драгалевци">93</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span> <span data-mean-id="1" data-signalization-id="9" title="">120</span> <span data-mean-id="1" data-signalization-id="9" title="лифт Симеоново">122</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2661">
					<li data-fill-value="message_number">ЦГМ-1942</li>
					<li data-fill-value="message_date">2021-06-19</li>
					<li data-fill-value="name">Задушница на 19.06.2021</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Бъкстон">4</span> <span data-mean-id="3" data-signalization-id="7" title="Задушница">7А</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2645">
					<li data-fill-value="message_number">ЦГМ-1933</li>
					<li data-fill-value="message_date">2021-05-28</li>
					<li data-fill-value="name">Временно изместване на спирка 2313</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Ман.Ливади">65</span> <span data-mean-id="1" data-signalization-id="9" title="">83</span> <span data-mean-id="1" data-signalization-id="9" title="Дружба">88</span> <span data-mean-id="1" data-signalization-id="9" title="Драгалевци">93</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span> <span data-mean-id="1" data-signalization-id="9" title="">120</span> <span data-mean-id="1" data-signalization-id="9" title="лифт Симеоново">122</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2618">
					<li data-fill-value="message_number">ЦГМ-1908</li>
					<li data-fill-value="message_date">2021-04-15</li>
					<li data-fill-value="name">Изместване на спирка 1377</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2595">
					<li data-fill-value="message_number">ЦГМ-1893</li>
					<li data-fill-value="message_date">2021-03-06</li>
					<li data-fill-value="name">Задушница на 06.03.2021</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Бъкстон">4</span> <span data-mean-id="3" data-signalization-id="7" title="Задушница">7А</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2578">
					<li data-fill-value="message_number">ЦГМ-1880</li>
					<li data-fill-value="message_date">2021-01-08</li>
					<li data-fill-value="name">Изместване на спирка 0413</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2398">
					<li data-fill-value="message_number">ЦГМ-1858</li>
					<li data-fill-value="message_date">2020-11-27</li>
					<li data-fill-value="name">Временно изместване на спирка 2313</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Ман.Ливади">65</span> <span data-mean-id="1" data-signalization-id="9" title="">83</span> <span data-mean-id="1" data-signalization-id="9" title="Дружба">88</span> <span data-mean-id="1" data-signalization-id="9" title="Драгалевци">93</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span> <span data-mean-id="1" data-signalization-id="9" title="">120</span> <span data-mean-id="1" data-signalization-id="9" title="лифт Симеоново">122</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2387">
					<li data-fill-value="message_number">ЦГМ-1847</li>
					<li data-fill-value="message_date">2020-11-07</li>
					<li data-fill-value="name">Задушница на 07.11.2020</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Бъкстон">4</span> <span data-mean-id="3" data-signalization-id="7" title="Задушница">7А</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2384">
					<li data-fill-value="message_number"></li>
					<li data-fill-value="message_date">2020-11-02</li>
					<li data-fill-value="name">Във връзка с подобряване на транспортното обслужване по линии на обществения градски транспорт</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Ст.Град">94</span> <span data-mean-id="1" data-signalization-id="9" title="Ив.Вазов">102</span> <span data-mean-id="1" data-signalization-id="9" title="">280</span> <span data-mean-id="2" data-signalization-id="4" title="">2</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Надежда">7</span> <span data-mean-id="3" data-signalization-id="7" title="">20</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2334">
					<li data-fill-value="message_number">ЦГМ-1797</li>
					<li data-fill-value="message_date">2020-09-12</li>
					<li data-fill-value="name">Във връзка с обект “Ремонт на бул. „България” ЕТАП 4 в участъка от бул. „Околовръстен път“ до ул. „Тодор Каблешков“</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2314">
					<li data-fill-value="message_number">ЦГМ-1778</li>
					<li data-fill-value="message_date">2020-08-16</li>
					<li data-fill-value="name">Във връзка с обект “Ремонт на бул. „България” ЕТАП 4 в участъка от бул. „Околовръстен път“ до ул. „Тодор Каблешков“</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/822bbb2b.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2311">
					<li data-fill-value="message_number">ЦГМ-1775</li>
					<li data-fill-value="message_date">2020-08-14</li>
					<li data-fill-value="name">Във връзка с обект “Ремонт на бул. „България” ЕТАП 4 в участъка от ул. „Тодор Каблешков“ до бул. „Околовръстен път“</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2298">
					<li data-fill-value="message_number">ЦГМ-1763</li>
					<li data-fill-value="message_date">2020-07-23</li>
					<li data-fill-value="name">Във връзка с обект “Ремонт на бул. „България” ЕТАП 3 в участъка от ул. „Тодор Каблешков“ до бул. „Гоце Делчев“</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2292">
					<li data-fill-value="message_number">ЦГМ-1755</li>
					<li data-fill-value="message_date">2020-07-15</li>
					<li data-fill-value="name">Във връзка с обект “Ремонт на бул. „България” ЕТАП 4 в участъка от ул. „Тодор Каблешков“ до бул. „Околовръстен път“</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																					<a href="public/uploads/event-attachments/9e7d5c8f.jpg" download="">1</a>
																		</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2280">
					<li data-fill-value="message_number">ЦГМ-1745</li>
					<li data-fill-value="message_date">2020-07-04</li>
					<li data-fill-value="name">Във връзка с обект “Ремонт на бул. „България” ЕТАП 2 в участъка от ул. „Тодор Каблешков“ до бул. „Гоце Делчев“</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2276">
					<li data-fill-value="message_number"></li>
					<li data-fill-value="message_date">2020-06-26</li>
					<li data-fill-value="name">Във връзка с летните фестивали „Музи на водата“, езерото Панчарево и сцена „Римски площад“ – Киноцентър Бояна“</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">1</span> <span data-mean-id="1" data-signalization-id="9" title="Горубляне">4</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2274">
					<li data-fill-value="message_number">ЦГМ-1741</li>
					<li data-fill-value="message_date">2020-06-17</li>
					<li data-fill-value="name">Временно изместване на спирка 0308</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2266">
					<li data-fill-value="message_number">ЦГМ-1735</li>
					<li data-fill-value="message_date">2020-06-06</li>
					<li data-fill-value="name">Задушница на 06.06.2020</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Бъкстон">4</span> <span data-mean-id="3" data-signalization-id="7" title="Задушница">7А</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2263">
					<li data-fill-value="message_number">ЦГМ-1731</li>
					<li data-fill-value="message_date">2020-05-25</li>
					<li data-fill-value="name">Временно изместване на спирка 2313</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Ман.Ливади">65</span> <span data-mean-id="1" data-signalization-id="9" title="">83</span> <span data-mean-id="1" data-signalization-id="9" title="Дружба">88</span> <span data-mean-id="1" data-signalization-id="9" title="Драгалевци">93</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span> <span data-mean-id="1" data-signalization-id="9" title="">120</span> <span data-mean-id="1" data-signalization-id="9" title="лифт Симеоново">122</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2258">
					<li data-fill-value="message_number">ЦГМ-1727</li>
					<li data-fill-value="message_date">2020-05-15</li>
					<li data-fill-value="name">Временно изместване на спирка 0308</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2243">
					<li data-fill-value="message_number">ЦГМ-1714</li>
					<li data-fill-value="message_date">2020-04-25</li>
					<li data-fill-value="name">Във връзка с обект “Ремонт на бул. „България” ЕТАП 2 в участъка от бул. „Гоце Делчев“ до ул. „Тодор Каблешков“</li>
					<li data-fill-value="tags"><span>спирка</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2231">
					<li data-fill-value="message_number">ЦГМ-1711</li>
					<li data-fill-value="message_date">2020-04-08</li>
					<li data-fill-value="name">НОВО РАБОТНО ВРЕМЕ НА НАЗЕМНИЯ ГРАДСКИ ТРАНСПОРТ ОТ 8 АПРИЛ 2020 ГОДИНА</li>
					<li data-fill-value="tags"></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="">1</span> <span data-mean-id="1" data-signalization-id="9" title="">3</span> <span data-mean-id="1" data-signalization-id="9" title="Горубляне">4</span> <span data-mean-id="1" data-signalization-id="9" title="">5</span> <span data-mean-id="1" data-signalization-id="9" title="">6</span> <span data-mean-id="1" data-signalization-id="9" title="">7</span> <span data-mean-id="1" data-signalization-id="9" title="">8</span> <span data-mean-id="1" data-signalization-id="9" title="">9</span> <span data-mean-id="1" data-signalization-id="9" title="">11</span> <span data-mean-id="1" data-signalization-id="9" title="">12</span> <span data-mean-id="1" data-signalization-id="9" title="">14</span> <span data-mean-id="1" data-signalization-id="9" title="">20</span> <span data-mean-id="1" data-signalization-id="9" title="">21/22</span> <span data-mean-id="1" data-signalization-id="9" title="">24</span> <span data-mean-id="1" data-signalization-id="9" title="">26</span> <span data-mean-id="1" data-signalization-id="9" title="">30</span> <span data-mean-id="1" data-signalization-id="9" title="">31</span> <span data-mean-id="1" data-signalization-id="9" title="">42</span> <span data-mean-id="1" data-signalization-id="9" title="О.Купел">45</span> <span data-mean-id="1" data-signalization-id="9" title="Мод.предградие">54</span> <span data-mean-id="1" data-signalization-id="9" title="">58</span> <span data-mean-id="1" data-signalization-id="9" title="">59</span> <span data-mean-id="1" data-signalization-id="9" title="Овча купел">60</span> <span data-mean-id="1" data-signalization-id="9" title="">63</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Ман.Ливади">65</span> <span data-mean-id="1" data-signalization-id="9" title="">67</span> <span data-mean-id="1" data-signalization-id="9" title="">69</span> <span data-mean-id="1" data-signalization-id="9" title="">72</span> <span data-mean-id="1" data-signalization-id="9" title="">73</span> <span data-mean-id="1" data-signalization-id="9" title="">74</span> <span data-mean-id="1" data-signalization-id="9" title="Г.Делчев">76</span> <span data-mean-id="1" data-signalization-id="9" title="">77</span> <span data-mean-id="1" data-signalization-id="9" title="Левски-Г">78</span> <span data-mean-id="1" data-signalization-id="9" title="">79</span> <span data-mean-id="1" data-signalization-id="9" title="Люлин">82</span> <span data-mean-id="1" data-signalization-id="9" title="">83</span> <span data-mean-id="1" data-signalization-id="9" title="">84</span> <span data-mean-id="1" data-signalization-id="9" title="">85</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Дружба">88</span> <span data-mean-id="1" data-signalization-id="9" title="Ст.Град">94</span> <span data-mean-id="1" data-signalization-id="9" title="">98</span> <span data-mean-id="1" data-signalization-id="9" title="">100</span> <span data-mean-id="1" data-signalization-id="9" title="Ив.Вазов">102</span> <span data-mean-id="1" data-signalization-id="9" title="">107</span> <span data-mean-id="1" data-signalization-id="9" title="">108</span> <span data-mean-id="1" data-signalization-id="9" title="">111</span> <span data-mean-id="1" data-signalization-id="9" title="">113</span> <span data-mean-id="1" data-signalization-id="9" title="">117</span> <span data-mean-id="1" data-signalization-id="9" title="">119</span> <span data-mean-id="1" data-signalization-id="9" title="">120</span> <span data-mean-id="1" data-signalization-id="9" title="">150</span> <span data-mean-id="1" data-signalization-id="9" title="">184</span> <span data-mean-id="1" data-signalization-id="9" title="">204</span> <span data-mean-id="1" data-signalization-id="9" title="">213</span> <span data-mean-id="1" data-signalization-id="9" title="">260</span> <span data-mean-id="1" data-signalization-id="9" title="">280</span> <span data-mean-id="1" data-signalization-id="9" title="Свобода">285</span> <span data-mean-id="1" data-signalization-id="9" title="3">294</span> <span data-mean-id="1" data-signalization-id="9" title="бул.България">304</span> <span data-mean-id="1" data-signalization-id="9" title="">305</span> <span data-mean-id="1" data-signalization-id="9" title="">306</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="1" data-signalization-id="9" title="">310</span> <span data-mean-id="1" data-signalization-id="9" title="">314</span> <span data-mean-id="1" data-signalization-id="9" title="">384</span> <span data-mean-id="1" data-signalization-id="9" title="">404</span> <span data-mean-id="1" data-signalization-id="9" title="">413</span> <span data-mean-id="1" data-signalization-id="9" title="">604</span> <span data-mean-id="2" data-signalization-id="4" title="">1</span> <span data-mean-id="2" data-signalization-id="4" title="">2</span> <span data-mean-id="2" data-signalization-id="4" title="Дружба">4</span> <span data-mean-id="2" data-signalization-id="4" title="Младост">5</span> <span data-mean-id="2" data-signalization-id="4" title="Люлин">7</span> <span data-mean-id="2" data-signalization-id="4" title="Г.Делчев">8</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="2" data-signalization-id="4" title="">11</span> <span data-mean-id="3" data-signalization-id="7" title="">3</span> <span data-mean-id="3" data-signalization-id="7" title="Бъкстон">4</span> <span data-mean-id="3" data-signalization-id="7" title="">5</span> <span data-mean-id="3" data-signalization-id="7" title="">6</span> <span data-mean-id="3" data-signalization-id="7" title="Надежда">7</span> <span data-mean-id="3" data-signalization-id="7" title="Люлин">8</span> <span data-mean-id="3" data-signalization-id="7" title="Зап.Парк">10</span> <span data-mean-id="3" data-signalization-id="7" title="">12</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span> <span data-mean-id="3" data-signalization-id="7" title="">20</span> <span data-mean-id="3" data-signalization-id="7" title="">22</span> <span data-mean-id="3" data-signalization-id="7" title="">23</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
							<ul class="ptrans-event-list-row list-row" data-entry-id="2196">
					<li data-fill-value="message_number">ЦГМ-1690</li>
					<li data-fill-value="message_date">2020-02-22</li>
					<li data-fill-value="name">Задушница на 22.02.2020</li>
					<li data-fill-value="tags"><span>задушница</span></li>
					<li data-fill-value="lines"><span data-mean-id="1" data-signalization-id="9" title="Задушница">18А</span> <span data-mean-id="1" data-signalization-id="9" title="">64</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">79А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">83А</span> <span data-mean-id="1" data-signalization-id="9" title="">86</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">86А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">90А</span> <span data-mean-id="1" data-signalization-id="9" title="Задушница">108А</span> <span data-mean-id="1" data-signalization-id="9" title="2">309</span> <span data-mean-id="2" data-signalization-id="4" title="">9</span> <span data-mean-id="3" data-signalization-id="7" title="Бъкстон">4</span> <span data-mean-id="3" data-signalization-id="7" title="Задушница">7А</span> <span data-mean-id="3" data-signalization-id="7" title="Орландовци">18</span></li>
					<li data-fill-value="attachments">
																								</li>
				</ul>
					</div>
	</section>
	<footer id="ptrans-event-list-total" class="list-total">
		общо
		<span id="ptrans-event-list-total-items" class="list-total-items">155</span>
		събития.
	</footer>
</div>
</div>
</div></main>